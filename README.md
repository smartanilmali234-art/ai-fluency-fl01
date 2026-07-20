# ai-fluency-fl01
# FL-01: AI Workflow Audit and Tool Setup
**Anil Mali | AI & Data Science, KLE College of Engineering & Technology (VTU) | ML Intern, FlyRank AI**

## 1. Task Classification Table

| # | Task | Classification | Rationale |
|---|------|----------------|-----------|
| 1 | Attending VTU lectures / labs for AI & DS coursework | Just me | Learning happens by doing the thinking myself; outsourcing comprehension defeats the point of the degree. |
| 2 | Solving problem sets / assignment derivations for coursework | Just me | Grades and exams test my own understanding, not AI's — using it here would hide gaps I need to know about. |
| 3 | Writing PyTorch training/eval scripts for FlyRank ML tasks | Collaborate with AI | I know the ML logic I want but AI speeds up boilerplate (data loaders, training loops); I still design the architecture and check outputs. |
| 4 | Debugging n8n workflow errors in LeadGenius AI | Collaborate with AI | Error messages are often cryptic; AI helps me reason through node configs faster, but I decide the actual fix since it touches live CRM data. |
| 5 | Writing/refining the OpenAI prompt that scores lead Fit (1–10) in LeadGenius AI | Collaborate with AI | Prompt wording directly affects output quality — this needs iterative back-and-forth with AI, not a one-shot delegation. |
| 6 | Validating scraped/enriched lead data (ScrapingBee/Firecrawl output) before it hits HubSpot | Delegate to AI with review | AI can flag malformed or suspicious scrapes quickly, but I do a final check before anything reaches the CRM. |
| 7 | Drafting weekly FlyRank internship status update/report | Delegate to AI with review | The structure is repetitive and AI drafts it well from my notes; I edit for accuracy and tone before sending. |
| 8 | End-to-end testing of the HubSpot CRM integration (contact creation, field mapping) | Just me | This is a live-system check — I need to actually click through and verify, not trust a description of what "should" work. |
| 9 | Summarizing AI/ML research papers or blog posts for self-study (e.g., Deep RL) | Collaborate with AI | AI accelerates a first pass, but I re-derive key equations/concepts myself so I actually retain them. |
| 10 | Writing git commit messages and inline code documentation | Delegate to AI with review | Low-stakes, formulaic writing — AI drafts, I skim and adjust before committing. |
| 11 | Drafting emails to professors/mentors/internship team | Delegate to AI with review | AI gets tone and structure right quickly; I personalize details and always read before sending — these are relationships, not just text. |
| 12 | Building/reviewing small React/Node.js UI pieces for side projects | Collaborate with AI | Faster to iterate on components with AI, but I own the architecture and UX decisions. |
| 13 | Planning weekly priorities across coursework, internship, and side projects | Collaborate with AI | AI helps me see conflicts/overload in my task list, but the actual prioritization call is mine — it doesn't know what matters most to me. |
| 14 | Formatting/cleaning routine data tables (e.g., experiment result logs) | Fully automate | Purely mechanical, same steps every time, easy to verify the output is correct at a glance. |
| 15 | Searching for/collecting reference links and documentation while researching a new tool or library | Fully automate | Retrieval task with no judgment call — AI can do this end-to-end and I just click through what's relevant. |

## 2. Toolkit Setup

- [x] Claude account created at claude.ai
- [x] ChatGPT account created at chat.openai.com
- [x] Anthropic Academy account created; enrolled in AI Fluency: Framework & Foundations
- [x] Completed Module 1

## 3. Claude Project — Custom Instructions

**Project name:** "Anil — AI Fluency Cohort"

> I'm Anil Mali, a Bachelor of Engineering student in Artificial Intelligence & Data Science at KLE College of Engineering & Technology (VTU), and a Machine Learning intern at FlyRank AI in Bengaluru. I'm currently building LeadGenius AI, an automated CRM lead-qualification agent (n8n, OpenAI API, HubSpot, ScrapingBee/Firecrawl). I'm interested in Data Science, applied AI, and Deep Reinforcement Learning, and I work mainly in Python/PyTorch, React, and Node.js.
>
> Tone: direct and technical, skip generic disclaimers, assume I know the fundamentals unless I say otherwise.
> Current goals: (1) build strong AI-collaboration habits for this fluency course, (2) ship LeadGenius AI, (3) grow as an ML engineer during my FlyRank internship.

![Claude Project Screenshot](claude-project-screenshot.png)

## 4. Three Target Tasks for FL-02–FL-04

| Task | "Done well" means |
|------|--------------------|
| **Prompt-tuning the LeadGenius AI Fit-Score node** | The AI-generated Fit Score (1–10) agrees with my own manual judgment on ≥8 of 10 test leads, and the 2-sentence summary correctly reflects the company's actual business (no hallucinated details) on every test case. |
| **Weekly FlyRank internship status report drafting** | First AI draft needs ≤2 rounds of edits before it's send-ready, accurately reflects that week's actual work with zero fabricated claims, and takes me under 10 minutes total (draft + review) versus writing from scratch. |
| **Deep RL paper/concept summarization for self-study** | I can explain the core idea back in my own words without notes afterward, the summary correctly identifies the paper's key contribution vs. prior work, and I catch at least one point where I'd push back on or want to verify the AI's explanation. |
