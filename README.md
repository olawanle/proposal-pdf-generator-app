# Proposal PDF Generator

A Windows desktop app that turns a list of web links into a polished,
formatted proposal PDF. Paste in source URLs, click **Generate**, and it
scrapes each page, rewrites the content into formal proposal language with
Claude, and compiles everything into a branded PDF with a cover page, table
of contents, and page numbers.

## Download

Grab the latest `ProposalPDFGenerator.exe` from the
**[Releases page](../../releases/latest)** - it's a single file, no
installation needed.

## Getting started

1. Download `ProposalPDFGenerator.exe` and run it (double-click - no install
   required).
2. On first launch it opens to **Settings**. Enter your Anthropic API key
   (there's a link in the app to get one at console.anthropic.com), plus
   your company name and logo if you'd like them on the cover page.
3. Click **Save Settings**.
4. Switch to **Generate**, paste in your source links (one per line), enter
   the client/agency name, and click **Generate Proposal PDF**.
5. Choose where to save it - once it's done you can open the PDF or its
   folder directly from the app.

Everything you enter in Settings (API key, branding, logo, proposal
sections) is saved on your own computer and reused every time - you only
set it up once.

## Notes

- Windows 10/11, 64-bit.
- Requires an internet connection (it calls the Claude API and fetches the
  pages you link to).
- Your API key never leaves your computer except to talk to Anthropic's API
  directly - it's not sent anywhere else.
