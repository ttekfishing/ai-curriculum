# AI-Powered Business Building

**A hands-on course for business owners who want to build their own tools, automations, and systems using AI — without hiring a dev team.**

Instructor: Cody
Format: 6-week cohort (core), 3-hour workshop (condensed), corporate B2B (customized)

---

## Table of Contents

1. [Course Overview](#course-overview)
2. [Prerequisites & Materials](#prerequisites--materials)
3. [Tools Covered](#tools-covered)
4. [6-Week Cohort Curriculum](#6-week-cohort-curriculum)
   - [Week 1: AI Landscape + Setup](#week-1-ai-landscape--setup)
   - [Week 2: Prompt Engineering for Code](#week-2-prompt-engineering-for-code)
   - [Week 3: Intro to Claude API](#week-3-intro-to-claude-api)
   - [Week 4: Building Real Business Tools](#week-4-building-real-business-tools)
   - [Week 5: Deploying & Sharing](#week-5-deploying--sharing)
   - [Week 6: Advanced — Agents, Automation & What's Next](#week-6-advanced--agents-automation--whats-next)
5. [3-Hour Workshop (Condensed Version)](#3-hour-workshop-condensed-version)
6. [Corporate B2B Training Adaptation](#corporate-b2b-training-adaptation)
7. [Pricing Strategy](#pricing-strategy)
8. [Instructor Notes](#instructor-notes)

---

## Course Overview

### The Promise

You don't need to become a software engineer. You don't need to hire a dev team. You need to know how to direct AI coding tools to build exactly what your business needs — and that's a skill you can learn in 6 weeks.

### Who This Is For

- Business owners and entrepreneurs running companies doing $500K–$10M+ in revenue
- Operators who are tired of paying for SaaS tools that do 80% of what they need
- People who have ideas for internal tools, dashboards, automations, or client-facing apps but don't know how to build them
- Anyone who has tried to hire developers and been frustrated by cost, timelines, or miscommunication

### Who This Is NOT For

- People looking for a computer science education
- Developers wanting to level up their AI skills (they should take a different course)
- Anyone not willing to open a laptop and build something

### What They'll Walk Away With

By the end of this course, every participant will have:

1. A working VS Code + Copilot setup they use daily
2. At least 2-3 custom tools built for their actual business
3. A deployed, live tool they can share with their team or clients
4. The confidence to scope, build, and iterate on new tools independently
5. A clear understanding of when to use AI tools vs. when to hire

### Instructor Credibility

Cody has built multiple production tools using these exact methods — advisor dashboards, lead generation tools, roadmap generators, client questionnaires, financial calculators — all as single-file HTML apps or simple Node.js backends, all built with AI assistance. No CS degree required. These tools are in active use today.

---

## Prerequisites & Materials

### Participant Prerequisites

- A laptop (Mac or Windows) — no tablets
- Basic computer literacy (you can install software, use a web browser, manage files)
- A real business problem you want to solve with a tool (bring this to Week 1)
- Willingness to type, make mistakes, and ask questions
- No prior coding experience required

### Required Accounts (set up before Week 1)

| Account | Cost | Purpose |
|---|---|---|
| [GitHub](https://github.com) | Free | Code hosting, Copilot access |
| [GitHub Copilot](https://github.com/features/copilot) | $10/mo (Individual) or $19/mo (Business) | AI code completions in VS Code |
| [Anthropic Console](https://console.anthropic.com) | Pay-as-you-go (typically $5–20/mo for learning) | Claude API access |
| [Vercel](https://vercel.com) | Free tier | Deploying tools to the web |
| [Netlify](https://netlify.com) | Free tier (backup option) | Alternative deployment |

### Required Software (installed before Week 1)

| Software | Download | Notes |
|---|---|---|
| VS Code | https://code.visualstudio.com | The code editor — non-negotiable |
| GitHub Copilot Extension | Install from VS Code Extensions | Search "GitHub Copilot" in Extensions |
| Node.js (LTS) | https://nodejs.org | For running backends and scripts |
| Git | https://git-scm.com | Version control (basic usage only) |
| A modern browser | Chrome or Edge recommended | For testing tools |

### Materials Provided by Instructor

- Starter templates for each week's project
- Prompt library (tested prompts that produce reliable output)
- Cheat sheets for HTML, CSS, JavaScript basics (reference only — not teaching these from scratch)
- Recorded walkthroughs of each exercise (for async review)
- Private Slack/Discord channel for cohort Q&A

---

## Tools Covered

### GitHub Copilot (Primary Tool — Weeks 1-5)

The daily driver. Copilot lives inside VS Code and does three things participants will use constantly:

- **Inline completions**: Start typing and Copilot finishes the thought. Tab to accept. This is the "autocomplete on steroids" that makes building 5-10x faster.
- **Copilot Chat (Cmd/Ctrl+I)**: Ask questions, get code generated, debug errors. This is the conversational interface inside the editor.
- **Workspace Agent (@workspace)**: Ask Copilot about your entire project. "How does the save function work?" "Where is the email validation?" It reads all your files and answers in context.

**When to use it**: Every session. Every project. It's the primary tool for building.

### Claude API / Anthropic SDK (Weeks 3-6)

When you want to build tools that think — summarize documents, draft emails, analyze data, answer questions — you need an LLM API. Claude is the best choice for business tool builders because:

- Strongest at following complex instructions
- Best at working with long documents (200K token context)
- Straightforward API, clear pricing
- Excellent at structured output (JSON, tables, reports)

**When to use it**: When your tool needs to read, write, analyze, or decide something using natural language.

### Claude Code CLI (Week 6 — Advanced)

The power tool. Claude Code is a command-line agent that can read your entire codebase, make changes across multiple files, run commands, and build features end-to-end from a single prompt. It's what Cody uses for complex builds.

**When to use it**: When you're comfortable with the basics and want to move faster on larger projects. Not for beginners — introduced in Week 6 as a graduation tool.

---

## 6-Week Cohort Curriculum

**Session format**: Each week is a 90-minute live session + homework
**Pace**: One session per week, homework due before next session
**Support**: Async Q&A in Slack/Discord between sessions

---

### Week 1: AI Landscape + Setup

**Theme**: Get oriented, get set up, get your first win.

#### Learning Objectives

1. Understand the current AI coding tool landscape and where each tool fits
2. Set up a complete development environment (VS Code, Copilot, Node.js, Git)
3. Write and run your first AI-generated script
4. Understand the difference between prompts, completions, and chat-based AI
5. Identify 2-3 real business problems you could solve with a custom tool

#### Pre-Work / Setup

- Install all required software (see Prerequisites)
- Create GitHub account and activate Copilot trial/subscription
- Watch the 10-minute "VS Code for Non-Developers" orientation video (provided)
- Write down 3 business problems you wish you had a tool for (bring to session)

#### Lesson Content

**Part 1: The AI Coding Landscape (20 min)**

- The big picture: AI didn't replace developers, it made building accessible
- Categories of AI coding tools:
  - Code completion (Copilot, Cursor, Codeium)
  - Chat-based coding (Copilot Chat, Claude, ChatGPT)
  - Agent-based coding (Claude Code, Cursor Composer, Devin)
  - API-based AI (Claude API, OpenAI API — for building AI into your tools)
- When to use what: a decision framework
- What's realistic: single-file apps, dashboards, automations, forms, calculators — NOT the next Salesforce
- Live demo: Show a real tool Cody built (advisor dashboard) — built entirely with AI, in active use

**Part 2: Environment Setup & First Script (40 min)**

- VS Code tour: files, terminal, extensions, Copilot icon
- Guided setup: verify Copilot is working (open a .js file, start typing, see suggestions)
- The terminal: what it is, basic commands (cd, ls, node filename.js)
- First script together: a business ROI calculator
  - Open a new file, type a comment describing what you want
  - Watch Copilot generate the logic
  - Run it in the terminal
  - Modify the prompt comment, see different output
- Key concept: **the comment IS the prompt** — Copilot reads your comments and code to predict what comes next

**Part 3: Prompts vs. Completions vs. Chat (20 min)**

- Inline completions: writing code with Tab (fast, automatic)
- Copilot Chat: asking for code, explanations, fixes (conversational)
- @workspace: asking about your whole project (contextual)
- Live demo: same task done three ways — calculate profit margin
- When each approach works best

**Part 4: Your Business Problem Workshop (10 min)**

- Each participant shares their #1 tool idea
- Quick feasibility check from Cody: "Yes, that's a Week 4 project" or "That's actually simpler than you think"
- Pair up ideas of similar complexity for peer support

#### Hands-On Exercise

**Build: A Business Expense Categorizer Script**

Using Copilot, participants build a Node.js script that:
- Takes a list of expenses (hardcoded array to start)
- Categorizes them (marketing, operations, payroll, etc.)
- Calculates totals by category
- Outputs a summary to the console

This is intentionally simple. The goal is experiencing the AI-assisted flow: comment → suggestion → Tab → run → iterate.

#### Homework

1. Modify the expense categorizer to read from a CSV file (use Copilot Chat: "How do I read a CSV file in Node.js?")
2. Add a "percentage of total" column to the output
3. Write down your #1 business tool idea in 3-5 sentences: What does it do? Who uses it? What problem does it solve?
4. Spend 15 minutes exploring Copilot Chat — ask it to explain any code you don't understand from the exercise

#### Key Takeaways

- AI coding tools are a skill, not magic. You learn to direct them.
- The quality of your prompt (comment, question, description) determines the quality of the output.
- You can build useful things on Day 1. The gap between "idea" and "working tool" just got much smaller.

---

### Week 2: Prompt Engineering for Code

**Theme**: The quality of what you build is determined by how well you communicate with AI.

#### Learning Objectives

1. Write effective prompts that produce working, production-quality code on the first try
2. Use iterative prompting to refine and improve AI-generated code
3. Build a complete, working business form with validation and calculations
4. Debug AI-generated code using Copilot Chat
5. Understand common failure modes and how to recover from them

#### Pre-Work

- Complete Week 1 homework (CSV expense categorizer)
- Read the provided "Prompt Patterns Cheat Sheet" (2 pages)
- Identify the form/calculator your business actually needs (you'll build a version of it this week)

#### Lesson Content

**Part 1: The Anatomy of a Good Prompt (20 min)**

- Why "build me a dashboard" fails and "build me a table that shows..." works
- The CRIS framework for code prompts:
  - **C**ontext: What are we building? What technology? What's already built?
  - **R**equirements: What specifically should it do? List the behaviors.
  - **I**nput/Output: What goes in? What comes out? Be explicit about data shapes.
  - **S**tyle: How should it look? Naming conventions? Error handling approach?
- Live demo: same feature, bad prompt vs. good prompt — side by side comparison
- Prompt length sweet spot: detailed enough to be unambiguous, short enough to stay focused

**Part 2: Iterative Prompting (20 min)**

- First pass: get the structure right
- Second pass: add validation, edge cases, error handling
- Third pass: polish the UI, add finishing touches
- Never try to do everything in one prompt — break it down
- Live demo: building a loan payment calculator in three passes
- The "fix this" loop: paste error → get fix → apply → repeat (this is normal and expected)

**Part 3: Common Failures & Recovery (15 min)**

- When Copilot suggests wrong code: how to reject and redirect
- When Chat gives you something that doesn't work: how to debug with AI
- The "context window" problem: when AI forgets what you're building
- Strategies: smaller files, clear comments, re-state requirements
- When to start over vs. when to iterate

**Part 4: Build Session (35 min)**

- Guided build of the hands-on exercise (below)
- Cody builds alongside participants, showing his screen
- Pause points for participants to catch up and ask questions

#### Hands-On Exercise

**Build: A Business Pricing Calculator**

A single HTML file that:
- Has a clean, professional form with inputs for: base cost, markup %, quantity, discount code, tax rate
- Calculates: subtotal, discount, tax, total, profit margin, per-unit price
- Validates all inputs (no negatives, required fields, reasonable ranges)
- Shows results in a styled output section
- Works entirely in the browser — no backend needed
- Looks good enough to show a client (CSS styling via Copilot)

Prompting approach (done step by step in session):
1. Prompt Copilot Chat: "Create an HTML file with a pricing calculator form" + specific field list
2. Iterate: "Add input validation — all fields required, no negative numbers, markup between 0-500%"
3. Iterate: "Add a results section that shows subtotal, discount amount, tax, total, profit margin, and per-unit cost"
4. Iterate: "Style it professionally — clean fonts, card layout, blue accent color, mobile-responsive"

#### Homework

1. Build a calculator or form specific to YOUR business. Examples:
   - A quoting tool for your services
   - A project cost estimator
   - A client intake form that calculates something useful
   - A commission calculator for your sales team
2. Write at least 5 different prompts to iterate on it. Save the prompts — you'll reference them later.
3. Make it look professional enough that you'd show it to a client or team member.
4. Bonus: Add a "Print" or "Export" button that formats the output nicely.

#### Key Takeaways

- Prompting is a skill that improves with practice. Your Week 6 prompts will be dramatically better than your Week 1 prompts.
- Break complex builds into 3-5 prompting passes. Don't try to build everything at once.
- If the AI gives you broken code, don't panic. Paste the error back into Chat and ask it to fix it. This loop is the normal workflow.
- A single HTML file can do a LOT. You don't need a complex setup to build useful tools.

---

### Week 3: Intro to Claude API

**Theme**: Make your tools intelligent. Add AI-powered reading, writing, and analysis.

#### Learning Objectives

1. Understand what an API is and how LLM APIs work (tokens, models, pricing)
2. Get an Anthropic API key and make a successful API call
3. Build a working AI-powered business tool using the Claude API
4. Understand token costs and how to estimate/control spending
5. Choose the right Claude model for different use cases

#### Pre-Work

- Create an Anthropic Console account at console.anthropic.com
- Add $10-20 in API credits (this will last weeks for learning)
- Generate an API key and save it securely
- Complete Week 2 homework (business-specific calculator/form)

#### Lesson Content

**Part 1: APIs Demystified (20 min)**

- An API is just sending a message and getting a response — like texting, but for software
- Live demo: make an API call using curl in the terminal (just to see it work raw)
- The anatomy of a Claude API call:
  - Endpoint (where to send it)
  - Headers (your API key — proves you're allowed)
  - Body (the messages — system prompt + user message)
  - Response (the AI's answer, plus metadata)
- Models available: Claude Sonnet (fast, cheap, good for most things), Claude Opus (powerful, slower, for complex tasks), Haiku (fastest, cheapest, for simple tasks)
- Tokens explained: what they are, how to count them, what they cost
- Real cost examples: "Summarizing a 10-page document costs about $0.02"

**Part 2: Your First API Call in Code (25 min)**

- Set up a Node.js project: `npm init`, `npm install @anthropic-ai/sdk`
- Environment variables: store your API key safely (never hardcode it)
- Write a script that sends a prompt to Claude and prints the response
- Modify the prompt, see different responses
- Add a system prompt: "You are a business consultant who gives concise, actionable advice"
- Key concept: **system prompts** shape the AI's personality and output format

**Part 3: Structured Output (15 min)**

- Getting Claude to return JSON instead of prose
- Using system prompts to enforce output format
- Parsing the response and using the data in your tool
- Live demo: send a customer review → get back structured sentiment analysis (JSON with score, keywords, summary, suggested action)

**Part 4: Build Session (30 min)**

- Guided build of the hands-on exercise

#### Hands-On Exercise

**Build: An AI-Powered Business Email Drafter**

A single HTML file with a Node.js backend that:
- Has a form with fields: recipient type (client/vendor/partner), purpose (follow-up, proposal, thank you, complaint resolution), key points (free text), tone (formal/friendly/urgent)
- Sends the form data to a Node.js endpoint
- The endpoint calls Claude API with a well-crafted system prompt
- Claude generates a professional email draft
- The draft displays on the page with a "Copy to Clipboard" button
- Includes a "Refine" button that sends the draft back with adjustment instructions

Backend structure:
```
project/
  index.html       (the form UI)
  server.js         (Express server + Claude API call)
  package.json
  .env              (API key — never committed to git)
```

Step-by-step build:
1. Use Copilot to scaffold the Express server with a single POST endpoint
2. Use Copilot Chat to write the Claude API integration
3. Build the HTML form with Copilot
4. Connect the form to the backend with a fetch call
5. Add the copy-to-clipboard and refine features

#### Homework

1. Extend the email drafter OR build a new Claude-powered tool for your business. Ideas:
   - A document summarizer (paste in a long document, get a summary)
   - A customer FAQ bot (give it your FAQ content as system prompt, let it answer questions)
   - A job posting generator (input role details, get a polished job post)
   - A meeting notes formatter (paste raw notes, get structured action items)
2. Experiment with different Claude models — try the same prompt with Haiku vs. Sonnet. Notice the speed and quality differences.
3. Track your API costs in the Anthropic Console. Calculate what it would cost if you used this tool 50 times per day.

#### Key Takeaways

- An API call is just sending a message and getting a response. The hard part is crafting the right prompt — and you already practiced that last week.
- System prompts are powerful. They let you turn Claude into a specialized tool for your exact use case.
- Costs are predictable and low. Most business tools cost pennies per use.
- The combination of a simple frontend + Claude API backend unlocks a huge range of tools you can build.

---

### Week 4: Building Real Business Tools

**Theme**: This is the week you build the tool you actually came here to build.

#### Learning Objectives

1. Build a complete, functional single-file HTML app using React CDN + Babel (no build step)
2. Implement localStorage for data persistence (save/load/delete)
3. Design a practical UI with multiple views and interactive features
4. Combine everything learned so far: Copilot, prompt engineering, Claude API integration
5. Plan and build a tool scoped to your actual business need

#### Pre-Work

- Finalize your personal tool concept. Write a 1-page spec answering:
  - Who uses this tool? (you, your team, your clients?)
  - What are the 3-5 core features it must have?
  - What data does it need to store?
  - Does it need AI (Claude API) features?
- Review the provided "React in 15 Minutes" cheat sheet (covers components, state, props — just enough to work with Copilot)
- Complete Week 3 homework

#### Lesson Content

**Part 1: The Single-File App Pattern (20 min)**

- Why this pattern: zero build tools, instant setup, easy to deploy, easy for AI to work with
- The stack: one HTML file containing:
  - React 18 via CDN (the UI library)
  - Babel standalone (lets you write modern JavaScript inline)
  - All CSS in a `<style>` tag
  - All JavaScript in a `<script type="text/babel">` tag
- Live demo: show the advisor dashboard Cody built — a real, production tool in a single HTML file
- When this pattern breaks down: very large apps, team collaboration, complex state management
- For 90% of internal business tools, this is all you need

**Part 2: localStorage — Your Free Database (15 min)**

- What localStorage is: browser storage that persists between sessions
- The four operations: save, load, update, delete
- Storing complex data: `JSON.stringify()` to save, `JSON.parse()` to load
- Live demo: save a list of clients, close the browser, reopen, data is still there
- Limitations: browser-specific, no sharing between devices, ~5MB limit
- When you need more: that's a future topic (databases, cloud storage)

**Part 3: Structuring Your App (15 min)**

- Planning your data model: what objects/fields do you need?
- Planning your views: what screens does the user see?
- Component thinking: header, sidebar, main content, modals — each is a reusable piece
- State management: what data changes as the user interacts?
- Walk through the structure of a real tool (advisor dashboard): App component → TabBar → ClientList → ClientDetail → Modal

**Part 4: Build Session (40 min)**

- This is the longest build session in the course
- Participants build their actual business tool
- Cody circulates and helps debug
- Guided fallback: participants who don't have a specific idea build the exercise below

#### Hands-On Exercise

**Build: A Client/Project Tracker Dashboard**

A single HTML file (React CDN + Babel) that:
- Shows a list of clients or projects in a table/card layout
- Has an "Add New" button that opens a modal form
- Stores all data in localStorage
- Has a detail view for each client/project (click to expand)
- Includes a search/filter feature
- Calculates and displays summary stats (total clients, revenue by status, average deal size)
- Has a clean, professional design (use Copilot to generate Tailwind-style CSS)

Features built step by step:
1. Scaffold: React app shell with a header and empty state
2. Data model: define the client/project object shape
3. Add form: modal with input fields, save to localStorage
4. List view: display all entries, delete button, edit button
5. Detail view: click an entry to see full details
6. Stats bar: calculate and display summary metrics
7. Search: filter the list by name or status

**For participants building their own tool**: use the same step-by-step approach. Cody helps them break their idea into these same 7 steps.

#### Homework

1. Finish your tool. It should be fully functional by next week — you're deploying it in Week 5.
2. Add at least one feature you didn't cover in the session. Use Copilot Chat to figure out how.
3. Have someone else try to use your tool (spouse, business partner, team member). Write down any confusion or friction they experienced.
4. (Optional) Add a Claude API feature to your tool — AI-generated summaries, recommendations, drafts, etc.

#### Key Takeaways

- A single HTML file can be a complete, functional business application. No framework setup, no build tools, no deployment pipeline.
- localStorage gives you instant data persistence. For internal tools and prototypes, it's often all you need.
- The hardest part is scoping. The most common mistake is trying to build too much. Start with 3 features, not 30.
- By the end of this week, you have a real tool that solves a real problem. That's not a toy project — that's a business asset.

---

### Week 5: Deploying & Sharing

**Theme**: Your tool is only useful if people can access it. Put it live.

#### Learning Objectives

1. Deploy a static site to Vercel or Netlify from a GitHub repository
2. Deploy a Node.js backend (for tools with Claude API calls)
3. Set up a custom domain (optional but covered)
4. Understand basic security considerations for business tools
5. Share a live tool with team members or clients via URL

#### Pre-Work

- Finish your tool from Week 4 (must be functional)
- Create accounts on Vercel (vercel.com) and GitHub (if not done already)
- Push your project to a GitHub repository (instructions provided — just follow them step by step)
- (Optional) Register a domain name if you want a custom URL

#### Lesson Content

**Part 1: Git & GitHub — Just Enough (20 min)**

- What Git does: tracks changes to your files (like Google Docs version history for code)
- What GitHub does: stores your code online (like Google Drive for code)
- The only commands you need:
  - `git init` — start tracking a project
  - `git add .` — stage your changes
  - `git commit -m "description"` — save a snapshot
  - `git push` — upload to GitHub
- Live demo: push the exercise project to GitHub in under 2 minutes
- .gitignore: keep your API keys and .env files out of GitHub (critical security step)

**Part 2: Deploying Static Sites (20 min)**

- What "static" means: HTML/CSS/JS files with no backend — they just need a web server to host them
- Vercel deployment:
  - Connect GitHub account
  - Import repository
  - Click deploy
  - Live URL in 60 seconds
- Live demo: deploy a participant's tool (with their permission) live during class
- Auto-deploy: every time you push to GitHub, Vercel automatically updates the live site
- Netlify as backup: same process, slightly different interface

**Part 3: Deploying Backends (15 min)**

- When you need a backend: Claude API calls, email sending, database access
- Vercel serverless functions: convert your Express routes to serverless functions
- Environment variables: store API keys in Vercel dashboard (never in code)
- Live demo: deploy the email drafter from Week 3 as a serverless function
- Alternative: Railway.app for always-on Node.js servers (if serverless doesn't fit)

**Part 4: Security & Sharing (15 min)**

- API keys: never in client-side code, never in GitHub, always in environment variables
- HTTPS: Vercel/Netlify give you this automatically
- Access control for internal tools:
  - Simple password protection (basic, not bank-grade — fine for internal dashboards)
  - Vercel password protection (Pro plan feature)
  - Netlify Identity (free, more setup)
- Sharing your tool: send the URL, pin it in Slack, bookmark it on team browsers
- Custom domains: buy on Namecheap/Google Domains, point DNS to Vercel (15-minute process)

**Part 5: Deploy Your Tool (20 min)**

- Guided deployment of each participant's tool
- Troubleshooting common issues (build errors, missing files, environment variable problems)
- Everyone leaves with a live URL

#### Hands-On Exercise

**Deploy: Your Week 4 Tool (Live on the Internet)**

By the end of this session, every participant has:
- Their project in a GitHub repository
- A deployed, live tool accessible via URL
- (If applicable) Environment variables configured for API keys
- A shareable link they can send to their team or clients right now

Steps:
1. Push to GitHub (guided, step by step)
2. Connect Vercel to GitHub
3. Import and deploy
4. Test the live URL
5. (If backend) Configure environment variables and redeploy
6. (Optional) Connect custom domain

#### Homework

1. Share your live tool with at least 3 people. Collect feedback.
2. Make at least one improvement based on feedback and push an update (watch it auto-deploy).
3. Write a 1-paragraph description of your tool — what it does, who it's for, and the URL. You'll use this in Week 6.
4. Explore the Vercel dashboard: check analytics, see deployment history, review logs.
5. (Optional) Set up a custom domain.

#### Key Takeaways

- Deployment is not the scary part. With modern tools, it's literally a 2-minute process.
- Auto-deploy from GitHub means your tool updates every time you push changes. No FTP, no server management, no devops.
- Security basics matter. API keys in client-side code is the #1 mistake — and the easiest to avoid.
- You now have a live tool on the internet that you built yourself. That's a real, tangible business capability.

---

### Week 6: Advanced — Agents, Automation & What's Next

**Theme**: Level up. Build AI into your tools, automate your workflows, and chart your path forward.

#### Learning Objectives

1. Understand what AI agents are and how they differ from simple API calls
2. Use Claude Code CLI for rapid, complex tool building
3. Add an AI-powered feature to an existing tool
4. Connect external APIs to expand tool functionality
5. Build a personal roadmap for continued AI-powered development

#### Pre-Work

- Install Claude Code CLI: `npm install -g @anthropic-ai/claude-code`
- Ensure Anthropic API key is set in environment
- Bring your deployed tool — you'll be adding an AI feature to it
- Read the provided "APIs You Can Connect" one-pager (Google Sheets, Slack, email, calendar, etc.)
- Think about repetitive tasks in your business that you wish were automated

#### Lesson Content

**Part 1: AI Agents — Beyond Single Prompts (20 min)**

- Single API call: "Summarize this document" → answer. Done.
- Agent: "Research this competitor, summarize their pricing, compare to ours, and draft a positioning email." The AI breaks this into steps, executes them, and delivers a result.
- Where agents are today: Claude Code, Cursor Composer, custom-built agents
- Live demo: use Claude Code to build a feature from a single natural-language description
  - "Add a PDF export button to this dashboard that generates a professional report"
  - Watch it read the codebase, write the code, and test it
- When agents are overkill vs. when they save hours

**Part 2: Claude Code CLI Deep Dive (25 min)**

- What it is: a command-line tool that reads your entire project and builds features by conversation
- Setup and basic usage:
  - Navigate to your project folder
  - Run `claude` to start a session
  - Describe what you want in plain English
  - Review the changes, approve or iterate
- Live demo: extend a participant's tool with a new feature using Claude Code
- Best practices:
  - Start with a clear, specific request
  - Let it read the codebase first (it needs context)
  - Review changes before approving
  - Iterate with follow-up instructions
- When to use Claude Code vs. Copilot Chat:
  - Copilot Chat: small changes, single-file edits, quick questions
  - Claude Code: multi-file changes, new features, complex logic, refactoring

**Part 3: Connecting External APIs (20 min)**

- What you can connect to (and why you'd want to):
  - Google Sheets API: read/write spreadsheet data (use Sheets as a database)
  - Slack API: send notifications, post updates
  - Email (nodemailer): send automated emails from your tools
  - Calendar APIs: schedule meetings, check availability
  - Stripe: accept payments
  - Webhooks: trigger actions when events happen
- Live demo: connect a tool to Google Sheets — read client data from a spreadsheet, display in dashboard
- The pattern: API key + endpoint + fetch call. Same structure every time.
- Using Copilot to write API integrations: "Write a function that reads rows from this Google Sheet and returns them as JSON"

**Part 4: Build Your AI Feature (25 min)**

- Each participant adds an AI-powered feature to their deployed tool
- Examples based on tool type:
  - Dashboard: "AI Summary" button that analyzes all clients and highlights concerns
  - Calculator: "AI Recommendations" based on the calculation results
  - Form: AI-generated follow-up email after form submission
  - Tracker: AI-powered categorization or prioritization of items
- Use Claude Code or Copilot Chat — participant's choice
- Deploy the update live during class

#### Hands-On Exercise

**Build: An AI-Enhanced Feature for Your Tool**

Each participant adds one AI-powered capability to their existing tool. The exact feature depends on their tool, but the pattern is the same:

1. Identify a point in the tool where AI analysis/generation would help
2. Add a button or trigger for the AI feature
3. Collect relevant data from the tool's state
4. Send it to Claude API with a well-crafted system prompt
5. Display the AI's response in the tool's UI
6. Deploy the update

Fallback exercise for anyone who finishes early or needs a guided option:

**Build: An AI-Powered Business Brief Generator**

A tool that:
- Takes basic company info (name, industry, size, challenge)
- Calls Claude API to generate a 1-page business brief
- Formats the output as a professional document
- Has a "Download as PDF" button (using browser print-to-PDF)
- Deployed and live

#### Homework (Final / Ongoing)

1. Finish and polish your tool. This is your portfolio piece.
2. Identify 2-3 more tools or automations you want to build in the next 90 days. Write a brief spec for each.
3. Set a calendar reminder for 30 days: "Build my next tool." Momentum matters.
4. (Optional) Build one of those tools using Claude Code from start to finish. Time yourself. Compare to your Week 1 speed.
5. Share your tool and your experience in the cohort channel. Celebrate the win.

#### Key Takeaways

- AI agents (like Claude Code) represent the next step: describing features in plain English and having them built for you.
- You're not limited to standalone tools. Connecting to APIs (Sheets, Slack, email) makes your tools part of your business workflow.
- The skills you learned in this course compound. Your 10th tool will take 10% of the time your 1st tool took.
- You don't need permission to build. You have the tools, the skills, and the pattern. Go build.

---

## 3-Hour Workshop (Condensed Version)

**Title**: "Build Your First AI-Powered Business Tool in 3 Hours"

This is the single-session version for local workshops, conferences, or corporate lunch-and-learns. Participants leave with one working tool.

### Agenda

| Time | Section | What Happens |
|---|---|---|
| 0:00–0:20 | **Intro & Setup** | What AI coding tools are. Quick VS Code + Copilot setup check. Show a real tool Cody built. |
| 0:20–0:45 | **Copilot Crash Course** | Inline completions, Chat, prompt engineering basics. Build a small calculator together. |
| 0:45–1:00 | **The Single-File App Pattern** | Explain React CDN + Babel approach. Show the structure. Provide a starter template. |
| 1:00–1:15 | **Break** | Help anyone with setup issues. |
| 1:15–2:30 | **Build Session** | Everyone builds a business tool from a template. Options: client tracker, pricing calculator, project dashboard, or their own idea. Cody circulates and helps. |
| 2:30–2:45 | **Deploy** | Push to GitHub, deploy on Vercel. Everyone gets a live URL. |
| 2:45–3:00 | **What's Next & Q&A** | Claude API teaser, Claude Code demo, cohort program pitch. |

### Workshop Materials

- Pre-configured starter templates (3 options: tracker, calculator, dashboard)
- One-page Copilot cheat sheet
- Step-by-step deployment guide (with screenshots)
- Follow-up email sequence (3 emails over 2 weeks) leading to cohort enrollment

### Workshop Logistics

- Max 20 participants (more than that, you can't help everyone debug)
- Require laptops — no "just watching" allowed
- Send setup instructions 1 week before and 1 day before
- Have a TA if group is over 12 (recruit a past cohort graduate)
- Room needs: Wi-Fi (confirm capacity for 20+ devices), power strips, projector

### Workshop-to-Cohort Conversion

The workshop is a funnel to the 6-week cohort. At the end:
- Show what's possible in 6 weeks vs. 3 hours
- Offer workshop attendees a discount on the next cohort ($200-300 off)
- Collect emails and follow up within 24 hours

---

## Corporate B2B Training Adaptation

### How to Customize for Teams

The 6-week cohort curriculum adapts to corporate training by changing the BUILD projects to match the company's actual needs. The teaching stays the same — the exercises become company-specific.

### Discovery Process (Before Training Starts)

1. **Stakeholder interview** (30 min with team lead or sponsor):
   - What tools does the team wish they had?
   - What repetitive tasks eat up the most time?
   - What's the tech comfort level of the group?
   - What data sources do they work with (Sheets, CRMs, internal systems)?

2. **Tool audit** (15 min):
   - What do they currently use? (Spreadsheets, Airtable, Notion, custom software?)
   - Where are the gaps?

3. **Custom project scoping**:
   - Design 2-3 build projects that solve real problems for this specific team
   - Replace the generic exercises in Weeks 2-4 with company-specific builds
   - The deployed tool in Week 5 should be something the team will actually use post-training

### Delivery Format Options

| Format | Duration | Best For |
|---|---|---|
| **Intensive** | 2 full days (back-to-back) | Teams that can block out time. Fastest to value. |
| **Weekly** | 6 x 90-minute sessions | Teams with full schedules. Allows homework between sessions. |
| **Hybrid** | 1 full day + 4 weekly follow-ups | Good kickoff energy + sustained learning. |
| **Embedded** | 4 hours/week for 3 weeks | For teams that want to go deep. Most hands-on time. |

### Customization Examples

**For a sales team**:
- Build: a prospect scoring tool, a proposal generator (Claude API), a deal tracker dashboard
- Connect to: their CRM data (export to CSV, or API if available)

**For an operations team**:
- Build: a process checklist app, an inventory tracker, a vendor evaluation tool
- Connect to: Google Sheets (existing data), Slack (notifications)

**For a marketing team**:
- Build: a content calendar tool, an AI blog post drafter, a campaign ROI calculator
- Connect to: social media APIs, Google Analytics exports

**For executive leadership**:
- Build: a KPI dashboard, a scenario planning calculator, an AI-powered briefing generator
- Focus on: decision-making tools, not operational tools

### Corporate Pricing

See Pricing Strategy section below for B2B rates.

### Deliverables for Corporate Clients

1. Pre-training setup guide (customized to their IT environment)
2. Custom-scoped build projects (2-3 tools designed for their needs)
3. All course materials and templates
4. 6 live training sessions (recorded)
5. 30-day post-training Slack support
6. 1 follow-up session (60 min) at 30 days to review progress and unblock issues
7. A written summary of tools built and recommended next builds

---

## Pricing Strategy

### 6-Week Cohort Program

| Tier | Price | Includes |
|---|---|---|
| **Standard** | $1,500 per person | 6 live sessions, all materials, Slack access, recordings |
| **Premium** | $2,500 per person | Standard + 2 x 30-min 1-on-1 sessions with Cody + priority Slack support |

**Cohort size**: 8–15 participants (enough for good discussion, small enough for individual help)

**Justification**:
- This is a high-value skill. Participants leave with working tools and the ability to build more.
- The alternative is hiring a developer at $100-200/hr. One custom tool build easily costs $5K-20K.
- After this course, participants can build those tools themselves, repeatedly, for free.
- $1,500 for a skill that saves $10K-50K+/year is an easy ROI story.
- Positioned above "watch a course on Udemy for $20" and below "hire a consultant for $10K." This is hands-on, live, with a real instructor and real outcomes.

### 3-Hour Workshop

| Setting | Price | Notes |
|---|---|---|
| **Public workshop** | $199–$299 per person | Local events, meetups, co-working spaces |
| **Conference session** | Negotiated with organizer | Typically free to attendees (Cody is paid as speaker or uses it as a funnel) |
| **Private workshop** | $3,000–$5,000 flat fee | For companies, groups, or organizations. Up to 20 participants. |

### Corporate B2B Training

| Format | Price |
|---|---|
| **Standard (6 sessions, up to 10 people)** | $10,000–$15,000 |
| **Premium (6 sessions + custom tools + 30-day support, up to 10 people)** | $15,000–$25,000 |
| **Additional participants** | $500–$1,000 per person |
| **Executive format (condensed, 2 days)** | $8,000–$12,000 |

**Justification for B2B**:
- Custom-scoped to their business = immediate ROI
- They get working tools out of the training, not just education
- Compare to hiring a consulting firm to build internal tools: $50K-200K
- Compare to SaaS licenses for 10 people: $500-2,000/month ongoing
- One-time investment that creates permanent internal capability

### Early-Bird & Bundle Discounts

- Early-bird (2+ weeks before cohort start): 15% off
- Workshop-to-cohort conversion: $200–$300 off cohort price
- Team bundle (3+ from same company in cohort): 20% off per person
- Alumni (past cohort members taking again): 50% off

---

## Instructor Notes

### General Teaching Philosophy

- **Build first, explain later.** Get something working, then explain why it works. Business owners learn by doing, not by listening.
- **Show your screen constantly.** Build alongside them. They should see you make mistakes, debug with AI, and iterate. This normalizes the process.
- **Use real tools you've built as examples.** The advisor dashboard, the lead gen tool, the roadmap generator — these are credibility and proof that the method works.
- **Don't teach programming.** Teach tool-building. The AI handles the programming. You teach them how to direct the AI.
- **Celebrate small wins.** When someone's calculator works for the first time, when their tool deploys, when they add a feature — make a moment of it. This is genuinely impressive for non-technical people.

### Week-by-Week Instructor Notes

**Week 1: AI Landscape + Setup**

- Expect 30-40% of participants to struggle with setup. Budget extra time. Have a TA if possible.
- The expense categorizer is intentionally underwhelming as a "tool." The point is experiencing the flow, not building something impressive. Set that expectation.
- When participants share their tool ideas, be honest about scope. If someone wants to build "the next Salesforce," gently redirect to a specific, achievable piece (e.g., "Let's start with a client list with follow-up reminders").
- End with energy. Show a 60-second demo of a tool you'll build by Week 4. Get them excited for what's coming.

**Week 2: Prompt Engineering for Code**

- The pricing calculator is the first "wow" moment. A complete, styled, functional tool from prompts alone. Lean into this.
- Common struggle: participants write prompts that are too vague. Have 3-4 "before/after" prompt examples ready to show.
- If someone's tool doesn't look good, show them how one Copilot Chat prompt can restyle the entire thing. CSS is where AI shines.
- Debugging is a teaching moment, not a failure. When something breaks (it will), walk through the fix publicly. "This is normal. Here's how we fix it."

**Week 3: Intro to Claude API**

- API keys and environment variables are the #1 confusion point. Go slow here. Show the exact steps. Have them verify their key works before moving to the build.
- The email drafter is genuinely useful. Some participants will start using it immediately. Encourage this.
- Costs: participants will worry about costs. Show the Anthropic Console usage page. Show that a day of learning used $0.50. Make costs concrete and unscary.
- If someone asks about OpenAI vs. Anthropic, keep it simple: "Both work. I teach Claude because it follows instructions better for the types of tools we're building. The patterns transfer."

**Week 4: Building Real Business Tools**

- This is the hardest week and the most rewarding. Participants are building their own thing, which means every problem is unique.
- Circulate constantly. Don't lecture for more than 10 minutes at a stretch. Most of this session should be hands-on with individual help.
- Have 2-3 backup project templates ready for participants who freeze on their own idea or pick something too ambitious.
- The localStorage concept clicks fast for most people — "Oh, it's like saving to a file, but in the browser." Use that analogy.
- Scope management is your main job this week. Cut features aggressively. "Let's get the list and add form working first. We can add charts next week."

**Week 5: Deploying & Sharing**

- This is the highest-energy session. Everyone gets a live URL. It feels real.
- Git/GitHub is the biggest mental hurdle. Don't teach branching, merging, pull requests — just init, add, commit, push. That's it.
- Have a backup plan for deployment failures. Netlify as a backup to Vercel. Manual upload as a backup to Git integration.
- Security talk: keep it practical, not scary. "Don't put API keys in HTML files. Use environment variables. Here's how." That's 90% of what they need.
- If time allows, deploy one tool live with the group watching. The 60-second deploy is impressive.

**Week 6: Advanced — Agents, Automation & What's Next**

- Claude Code demo is the "future" moment. Show something genuinely complex being built from a single conversation. Aim for jaws dropping.
- API connections (Sheets, Slack, etc.) — demo, don't deep-dive. Show that it's possible and provide resources. Participants who want to go deeper will.
- The AI feature addition is the final project. Make sure everyone has something to show. Even a simple "AI Summary" button counts.
- End the course strong. Each participant should share their tool, what it does, and what they learned. Make it a mini-demo day.
- Close with: "You're now someone who can build software for their business. That's a permanent skill. Go use it."

### Common Participant Questions & Answers

**"Is this going to be obsolete in 6 months?"**
The specific tools will evolve, but the skill — directing AI to build what you need — is permanent and only gets more powerful. The patterns you learn (prompt engineering, API integration, deployment) transfer to every new tool that comes out.

**"Can I really build something useful without knowing how to code?"**
Yes, and you'll prove it to yourself by Week 2. You won't understand every line of code the AI writes — and you don't need to. You need to understand what you're building, how to describe it, and how to test if it works.

**"What if my tool needs to handle sensitive data?"**
For truly sensitive data (health records, financial data, PII), you need proper security beyond what this course covers. We teach the basics (HTTPS, API key management, environment variables), which is sufficient for internal tools and non-sensitive use cases. If you're handling regulated data, you'll need to consult a security professional for the final production version.

**"How is this different from no-code tools like Bubble or Retool?"**
No-code tools are great until you hit their limits — and you will. They lock you into their platform, charge monthly fees, and can't do everything you need. With AI-assisted coding, you own the code, pay nothing ongoing (except hosting, which is usually free), and can build anything. It's harder to start but much more powerful long-term.

**"I don't have a technical co-founder / CTO. Can this replace that?"**
For internal tools, dashboards, automations, and simple client-facing apps — yes. For a complex software product that IS your business — no, you'll still need technical expertise. But you'll be a much better buyer of that expertise because you understand what's possible and what things should cost.

---

## Appendix: Cohort Schedule Template

### Suggested Timeline

| Week | Date | Topic | Homework Due |
|---|---|---|---|
| 0 | (1 week before) | Setup & Pre-Work | Software installed, accounts created |
| 1 | Day 1 | AI Landscape + Setup | CSV expense categorizer |
| 2 | Day 8 | Prompt Engineering for Code | Custom business calculator/form |
| 3 | Day 15 | Intro to Claude API | Extended AI-powered tool |
| 4 | Day 22 | Building Real Business Tools | Polished tool, user-tested |
| 5 | Day 29 | Deploying & Sharing | Live deployed tool with feedback |
| 6 | Day 36 | Advanced + Demo Day | Share and celebrate |

### Between-Session Support

- Slack/Discord channel: monitored by Cody, responses within 24 hours on business days
- Office hours: 30-minute optional drop-in before each session for debugging help
- Peer support: encourage participants to help each other in the channel
- Resources shared in channel: relevant articles, new tool announcements, tips and tricks
