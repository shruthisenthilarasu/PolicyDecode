# Policy Decoder

AI-powered regulatory document analyzer. Upload any zoning code, QAP, or land use policy and ask questions in plain English. Built for real estate developers who need to understand complex regulatory requirements before committing to a site.

## What It Does

Real estate developers spend weeks combing through regulatory documents — 200+ pages of legal language just to answer basic questions about a site. Policy Decoder reads them for you.

- Ask any question about a document in plain English
- Get clear, direct answers sourced from the document
- When the document doesn't cover something, Claude fills in the gap and labels it clearly
- Works with any PDF, TXT, or Markdown policy file

## Pre-loaded Document

The 2026 Texas Qualified Allocation Plan (QAP) — the rulebook that governs housing tax credit site selection statewide. Covers site scoring criteria, disqualifiers, zoning requirements, underwriting rules, and application deadlines.

## How It Works

1. Select the pre-loaded QAP or upload your own document
2. Use a quick-question preset or type your own question
3. The AI searches the most relevant pages and returns a plain English answer
4. Green blocks = sourced from the document. Yellow blocks = filled in from Claude's general knowledge

## Tech Stack

- Vanilla HTML/CSS/JS — no framework, no build step
- [PDF.js](https://mozilla.github.io/pdf.js/) for client-side PDF text extraction
- [Anthropic Claude API](https://www.anthropic.com) (claude-sonnet-4) for document analysis
- Keyword-based page retrieval to surface relevant sections from large documents

## Running Locally

Just open `index.html` in a browser. No server required.

## Deployment

Deployed on Vercel. To deploy your own instance, drag `index.html` into [vercel.com/new](https://vercel.com/new).

## Built For

DevelopMate — because the best site decisions happen before the expensive reports do.
