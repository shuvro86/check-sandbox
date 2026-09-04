# Shreehan Workspace

A client-rendered Next.js dashboard for Shreehan (Class 2, Maple Leaf
International School), covering the six study material types tracked in the
Shreehan HQ Notion workspace: Routine, Syllabus, Study Notes, Assignments,
Exam, and Unseen Paper. Includes Shreehan's Digital Twin, an AI chat
grounded in the same data shown on the dashboard, powered by OpenRouter.

The content in `src/data/` is synced from the real attachments in the
Shreehan HQ Notion workspace (downloaded to this project's `download/`
directory via the Notion API, then transcribed into typed data here). The
original PDFs/images are also served from `public/files/` and linked from
each section of the dashboard.

## Development

```bash
npm install
npm run dev
```

Open http://localhost:3000. Requires `OPENROUTER_API_KEY` in `.env.local`
for the AI chat (see `.env.local` in this directory).

## Testing

```bash
npm run test      # unit tests (Vitest + React Testing Library)
npm run test:e2e  # end-to-end tests (Playwright)
```

## Build

```bash
npm run build
npm run start
```
# check-sandbox
