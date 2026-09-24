[README.md](https://github.com/user-attachments/files/32614686/README.md)
# Application Tracker

A free, private tracker for graduate job applications. Open it in your browser to:

- see every firm you've applied to and which stage you've reached
- keep an interview prep page for each firm, with facts linked to their sources and a tick box for each fact you've checked
- log what happened at each stage
- record each firm's rules on using AI, stage by stage

**[Open the tracker](https://YOUR-USERNAME.github.io/job-tracker/)** ← replace with your GitHub Pages link

## Privacy

Everything you type stays in your own browser on your own device. There is no account and no server, and nothing is sent anywhere. Use **Download backup** now and then so you don't lose your notes if you clear your browser data or change device.

## How to use it

1. Delete the example application, or read it first to see how the tracker works.
2. Click **+ Add application**. Copy the stages from the firm's careers page.
3. Open the firm and use the **AI rules** tab to record what the firm allows at each stage, with a link to its official policy.
4. Add facts to the prep page with sources. Tick each one once you've checked the source yourself.
5. Update **Stages and log** after each stage.

## How I built it

I built this tracker as a first draft, working with AI and taking the key decisions myself. I set the purpose and the features, reviewed each version, and set it up on GitHub Pages myself. The sections below cover why I built it, how I used AI, what I changed, and where I chose not to use it.


**Why I built it:**
I'm applying to graduate programmes at large firms. Each one has several stages, its own deadlines and its own rules. I wanted one place to see every application, the stage I'd reached, my interview prep and my notes from each stage. The world of work is changing, and AI is becoming part of everyday roles. I wanted this project to show that I can use AI ethically and with good judgement.

**How I used AI:**
I built this with Claude, an AI assistant. I decided what the tracker needed:

a visual view of every firm I've applied to
the stage I'm at in each firm's process
a page for each company, with interview prep and information about the firm
a log of what happened at each stage

I asked the AI to research each firm's application process, its background and its rules on AI, and then to build the tracker. I decided to make a public version for other people too. That meant removing my personal information and saving data only in each user's own browser. I set it up on GitHub Pages myself.

**What I checked or changed:**
This is a first draft, and reviewing it has already shaped the next version.

Setting the direction: the AI started building before I'd explained what I wanted, and it began researching another role I'd applied for elsewhere. I stopped it and set out my own requirements.
Reviewing the design: the colours and layout felt too plain, some headings were not clear enough, and the link in the README didn't work. For the next version I plan to make the design more engaging, make the headings clearer, and rename "Key facts" to "Information about the firm". I'm keeping the parts that worked well: the log for each stage, the AI rules for each firm, and a source on every fact.
Checking the facts: every fact about a firm links to its source, and I only rely on a fact once I've confirmed it myself.

**Where I chose not to use AI:**
I used AI for research and building, but not in the recruitment process itself. My assessment and interview answers are my own, as each firm's guidelines ask, and I keep other people's personal information out of AI tools. That's why this version of the tracker starts blank: the answers section is left for each person to write in their own words.

## Tech

A single HTML file with no dependencies apart from Google Fonts. Data is saved with the browser's `localStorage`.
