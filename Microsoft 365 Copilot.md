# Microsoft 365 Copilot — Hands-On Lab Guide

> **Course:** AB-731 &nbsp;|&nbsp; **Mode:** Self-Paced

A practical, step-by-step lab guide for learning Microsoft 365 Copilot across Chat, Word, Excel, PowerPoint, Outlook, and Teams. Each lab includes a goal, steps, a verification checkpoint, and a Note.

---

## Table of Contents

- [Before You Begin](#before-you-begin)
- [Lab 1 — First Contact: Copilot Chat](#lab-1--first-contact-copilot-chat)
- [Lab 2 — Create Content in Chat Mode](#lab-2--create-content-in-chat-mode)
- [Lab 3 — Create Content with the PowerPoint Agent](#lab-3--create-content-with-the-powerpoint-agent)
- [Lab 4 — Word: Draft a Business Proposal](#lab-4--word-draft-a-business-proposal)
- [Lab 5 — PowerPoint: Improve an Existing Deck](#lab-5--powerpoint-improve-an-existing-deck-for-executives)
- [Lab 6 — Excel: Summarize & Explore a Workbook](#lab-6--excel-summarize--explore-a-workbook)
- [Lab 7 — Outlook: Triage & Draft Email](#lab-7--outlook-triage--draft-email)
- [Lab 8 — Teams: Meeting Recap & Catch-Up](#lab-8--teams-meeting-recap--catch-up)
- [Lab 9 — Research a Report in Chat](#lab-9--research-a-report-in-chat)
- [Wrap-Up](#wrap-up-what-you-practiced)

---

## Before You Begin

### Prerequisites

- A Microsoft 365 account with a **Microsoft 365 Copilot license** assigned
- Microsoft 365 desktop apps installed and signed in (Word, Excel, PowerPoint, Outlook, Teams) — current Microsoft 365 channel
- Microsoft 365 Copilot Chat available at **[m365copilot.com](https://m365copilot.com)** or via the Copilot app in Teams
- A modern browser (Edge or Chrome) signed in with your work account

### The Prompt Formula (G-C-E)

Every good Copilot prompt has three parts. Keep this in mind for each lab:

| Part | Meaning | Example |
|------|---------|---------|
| **Goal** | What you want | "Create a 5-slide presentation…" |
| **Context** | Why / for whom | "…for executive leadership" |
| **Expectations** | Format, tone, length | "…concise, with speaker notes" |

### Two Ways to Run Copilot (you'll use both)

- **Chat mode** → conversational, grounds on your work data + web, returns text/markdown you copy out.
- **Agent / in-app** → Copilot built into the app (PowerPoint, Word, Excel, Outlook, Teams) that *acts on the content directly*.

---

## Lab 1 — First Contact: Copilot Chat

**Goal:** Get oriented and confirm your environment works.

1. Open **[m365copilot.com](https://m365copilot.com)** (or Copilot in Teams) and sign in with your work account.
2. Confirm you see the **"Work"** toggle (grounded on tenant data) vs **"Web"**.
3. Type a warm-up prompt:
   > Summarize what Microsoft 365 Copilot can do for me in 5 bullet points.
4. Observe the response and any **referenced sources** (work content shows citation chips).

✅ **Checkpoint:** You get a response and can switch between Work and Web modes.

---

## Lab 2 — Create Content in Chat Mode

**Goal:** Generate a presentation outline using **Copilot Chat** (text output).

1. In Copilot Chat, enter:
   > Create a 5-slide presentation about AI adoption in retail.
2. Review the output — Chat returns a **structured outline** (titles + talking points), not an actual `.pptx`.
3. Refine with a follow-up:
   > Add a slide on ROI and rewrite the titles to be punchier.

✅ **Checkpoint:** You have a 5–6 slide outline as text.

💡 **Note:** Chat *plans and drafts* content; it does not build the file. That's the job of Lab 3.

---

## Lab 3 — Create Content with the PowerPoint Agent

**Goal:** Build the **actual slide deck** using Copilot *inside* PowerPoint, then compare to Lab 2.

1. Open **PowerPoint** → new blank presentation.
2. Open **Copilot** (Home tab → Copilot) and enter:
   > Create a 5-slide presentation about AI adoption in retail.
3. Watch Copilot **generate real slides** with layouts, titles, and content.
4. Compare side-by-side with your Lab 2 outline.

✅ **Checkpoint:** A real `.pptx` with ~5 slides exists.

| | Lab 2 — Chat Mode | Lab 3 — PPT Agent |
|---|---|---|
| Output | Text outline | Real slides |
| Acts on file | No | Yes |
| Best for | Planning, ideation | Building the deliverable |

💡 **Note:** Same prompt, very different result — *where* you run Copilot matters as much as *what* you ask.

---

## Lab 4 — Word: Draft a Business Proposal

**Goal:** Use Copilot in Word to draft a structured document.

1. Open **Word** → new blank document.
2. Open **Copilot** → **"Draft with Copilot."**
3. Paste this prompt:
   > Create a project proposal to implement Microsoft 365 Copilot in our organization. Include these sections:
   > - Executive Summary
   > - Business Benefits
   > - Implementation Approach
   > - Risks and Mitigations
   >
   > Use professional business language.
4. Click **Generate**, then **Keep it**.
5. Refine a section — select the **Risks** heading and prompt:
   > Expand this into a table with columns: Risk, Likelihood, Mitigation.

✅ **Checkpoint:** A proposal with all four sections and a risk table.

💡 **Note:** Naming the exact sections forces structure — vague prompts give vague documents.

---

## Lab 5 — PowerPoint: Improve an Existing Deck for Executives

**Goal:** Use Copilot to *refine* (not create) a presentation.

1. Open an existing deck (use your Lab 3 deck, or any sample).
2. Open **Copilot in PowerPoint** and enter:
   > Improve this presentation for executive leadership: add visual impact and create concise speaker notes.
3. Review the changes — tightened text, visual suggestions, and **speaker notes** added per slide.
4. Follow-up to polish:
   > Make every slide title under 8 words and add one key metric per slide.

✅ **Checkpoint:** Deck has executive-ready slides **and** speaker notes.

💡 **Note:** Copilot is as useful for *editing existing content* as for creating new content.

---

## Lab 6 — Excel: Summarize & Explore a Workbook

**Goal:** Use Copilot to interpret data and guide your next steps.

1. Open any Excel workbook with data formatted as a **Table** (Insert → Table). *Copilot in Excel works best on structured tables.*
2. Open **Copilot** and enter:
   > Please quickly provide a summary of this workbook that I can read in a few seconds. Help me understand what the workbook contains and any initial insights. Then ask me at most 3 questions to help me decide what to explore next based on that summary.
3. Read the summary and answer one of Copilot's 3 questions.
4. Act on a suggestion, e.g.:
   > Add a column that flags rows above the average value.

✅ **Checkpoint:** You get a quick summary, insights, and 3 guiding questions.

💡 **Note:** Asking Copilot to *ask you questions* turns it into an analysis partner, not just a generator.

---

## Lab 7 — Outlook: Triage & Draft Email

**Goal:** Use Copilot in Outlook to summarize a long thread, draft a reply, and coach your tone.

1. Open **Outlook** (new Outlook or web) and open a **long email thread** (5+ replies).
2. At the top of the message, click **Summary by Copilot** to get a bulleted recap with cited messages.
3. Read the summary, then start a reply and choose **Draft with Copilot**:
   > Draft a reply confirming I'll attend the project kickoff, ask for the agenda in advance, and propose Thursday 2 PM as an alternative if needed. Keep it friendly and concise.
4. Before sending, use **Coaching by Copilot** on your draft:
   > Review my draft for tone, clarity, and professionalism, and suggest improvements.
5. Apply a suggestion and adjust the **tone/length** options Copilot offers (e.g., *Make it more formal / shorter*).

✅ **Checkpoint:** You have a thread summary, a generated reply, and at least one coaching suggestion applied.

💡 **Note:** In Outlook, Copilot does three distinct jobs — **summarize** (read faster), **draft** (write faster), and **coach** (send better). Use the right one for the moment.

---

## Lab 8 — Teams: Meeting Recap & Catch-Up

**Goal:** Use Copilot in Teams to catch up on a meeting and an active chat.

> **Setup note:** Copilot meeting recap requires the meeting to be **recorded and/or transcribed**. For the lab, join or replay a recorded test meeting, or use one from your tenant.

1. Open a recorded meeting in **Teams → Calendar → the meeting → Recap**.
2. Open **Copilot** in the recap and ask:
   > Summarize the key decisions and list all action items with their owners.
3. Follow up to focus on yourself:
   > What was said about me or assigned to me? Did I have any open questions?
4. Switch to a busy **Teams chat or channel** you missed, open **Copilot**, and ask:
   > Catch me up on this conversation since yesterday and highlight anything that needs my response.
5. (Optional) During a **live meeting**, open Copilot and ask *"What are the main points so far?"* without interrupting.

✅ **Checkpoint:** You get decisions, owner-assigned action items, a personalized "what's mine," and a chat catch-up.

💡 **Note:** Copilot in Teams turns hours of meetings and chat backlog into **decisions, action items, and your personal follow-ups** — but only when content is transcribed/available.

---

## Lab 9 — Research a Report in Chat

**Goal:** Use Copilot Chat (Web mode) to draft a research-based report.

1. Open **Copilot Chat** and switch to **Web** mode (for current public info).
2. Enter:
   > Draft a report on the latest AI Summit held in Delhi in 2026. Include key themes, notable announcements, and takeaways for enterprise IT leaders.
3. Review **citations**, then refine:
   > Reformat as an executive brief: 1 paragraph summary + 5 bullet takeaways.
4. Copy the result into Word (links back to Lab 4 workflow).

✅ **Checkpoint:** A cited, well-structured report.

💡 **Note:** Use **Web** mode for current external info; use **Work** mode for tenant/company data. Always verify citations.

---

## Wrap-Up: What You Practiced

| Lab | App | Skill |
|-----|-----|-------|
| 1 | Chat | Orientation, Work vs Web |
| 2 | Chat | Drafting/planning content |
| 3 | PowerPoint | Creating a real deliverable |
| 4 | Word | Structured document drafting |
| 5 | PowerPoint | Refining existing content |
| 6 | Excel | Data summary & guided analysis |
| 7 | Outlook | Summarize, draft & coach email |
| 8 | Teams | Meeting recap & chat catch-up |
| 9 | Chat | Research with citations |

### Key Takeaways

1. **Goal–Context–Expectations** makes every prompt better.
2. **Chat plans; agents build** — choose the right surface.
3. **Iterate** — your first response is a draft, not the final answer.
4. **Verify** citations and data before you trust them.

---

*Lab guide for Microsoft 365 Copilot — Course AB-731.*
