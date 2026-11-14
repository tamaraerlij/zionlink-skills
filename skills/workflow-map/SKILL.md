---
name: workflow-map
description: Step 5 of ZionLink Market Entry. Maps the commercial and expansion work a team repeats, ranks which tasks are the best candidates for Claude and which should stay human, and saves a one page Commercial Work Map. Use when someone types /zionlink-market-entry:workflow-map, or asks "what can I automate", "where can AI help my sales team", "map my repeated work".
---

# Step 5: Map your commercial work

This step works on its own. It is better after steps 1 to 4, but it does not need them. Use simple English, short sentences, one question at a time, and no dashes in prose (dates, file names, list bullets, table lines and web addresses are fine). Wait for approval before saving.

## Rules
- Scope is **commercial and expansion work only**: finding companies, researching them, writing to them, following up, preparing calls, logging notes, reporting. Do not map finance, legal, HR or product work. If the person lists one, say it is outside this map and leave it out.
- All numbers come from the person. Never invent hours, savings, rates or percentages. If they do not know, ask for a rough guess and label it "estimate by you".
- Everything is a **hypothesis to test, not a verified result**. No promise of time saved.
- Never send, post or change anything for the person. Drafts only. Never suggest that Claude contact buyers on its own.
- Do not claim Claude can verify a company, a person or a market fact. That needs real sources.

## What to do
1. Look for `zionlink-market-entry.md` in the current folder. If it exists, use the company, what it sells and the buyer from it, and do not ask again. If not, ask only: "What does your company sell?" and "Who is on the team that sells or expands?"
2. Ask: "Which tasks did your team repeat in the last two weeks to find, contact or follow up buyers?" Give these as prompts, not as a fixed list: researching a company, writing a first message, following up, preparing a call, answering replies, taking notes or updating a CRM, writing a report for a manager, adapting a message or material to another language. The person can add their own. Take up to 8 tasks.
3. For each task, ask one thing at a time:
   - How often? (per week)
   - How long does it take each time? (minutes)
   - What goes in? (for example: a company website, call notes)
   - What comes out? (for example: a draft message, a summary)
   - If it is wrong, what is the cost? Low, medium or high.
4. Calculate for each task: hours per month = times per week x 4 x minutes / 60. Show it as "estimate by you".
5. Rank the tasks. A task is a **good candidate** when all of these are true:
   - It repeats at least once a week.
   - The input and the output are clear.
   - A wrong result costs low or medium, and a person can check it before it is used.
   - It does not need verified facts about a real company or person.
   A task is **not a candidate yet** when it sends something automatically, commits money or terms, needs a verified fact, or has no clear output. Give the reason in one line.
6. Show the result:
   - **Top 3 candidates** in a table: task, hours per month (estimate by you), input, output, who approves.
   - **Keep human for now:** the tasks that did not pass, with the reason.
   - **One suggested first task** and why (most hours, clearest input and output, lowest risk).
7. Ask: "Is this right? What should change?" Edit until approved.
8. Save a one page `commercial-work-map.md` in the current folder: company, the ranked table, the human list, the first task, and the open hypotheses to test (for example "this task really takes 40 minutes, check for one week"). If `zionlink-market-entry.md` exists, mark step 5 approved with today's date.

## Close: what comes next
Tell the person in simple words:
- This map is a **starting hypothesis** built from their own numbers. Test it for one week before relying on it.
- They can ask Claude to write a skill for their first task, using the input and output from the map. They approve every result before using it.
- If they want ZionLink to review the map and build a custom skill for their team, they can say so in **First Link**: https://zionlink.io/first-link.html (the question about repeated tasks is there).

Do not push. Offer once, then stop.
