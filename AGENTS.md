# practice-Capstone1 — Agent Instructions

This is the canonical repository-level contract for agents working on this capstone practice repository.

## Repository identity

This is a small static resume/portfolio learning exercise. The current implementation is plain HTML plus local image assets. The original requirements embedded in `index.html` explicitly constrain the capstone to **HTML only**.

Do not invent Node/npm commands, build tooling, frameworks, automated tests, deployment infrastructure, or application architecture that are not present.

## Required reading

1. `README.md`.
2. `.agent/STATE.md` and `.agent/PLANNER_HANDOFF.md`.
3. `index.html`, including the preserved capstone specification comments, before changing scope.
4. `.agent/EXECUTION_PROMPT.md` if one is later created; reconcile it with current `main` before resuming.

## Scope guardrail

By default, preserve the HTML-only exercise constraint. CSS, JavaScript, React, build tooling, package managers, backend services, and large portfolio redesigns are scope changes, not routine cleanup. Add them only when an explicit task deliberately supersedes the capstone constraint and update the documentation/state at the same time.

## Validation

There is currently no automated build or test suite. Validate HTML changes by inspecting the affected source and rendering the pages in a browser when browser access is available. Verify local links and image references. Do not convert “file opened successfully” into a broader compatibility claim.

## Content and privacy discipline

The pages contain personal resume-style material and local photos. Treat those files as intentional user content. Do not invent, embellish, infer, publish, or replace personal facts merely to make the resume look more complete. Make personal-content edits only when explicitly requested or directly supported by repository evidence.

## Documentation and Git safety

Keep living docs truthful about the repository's learning/static nature. Preserve historical exercise comments unless a scoped cleanup explicitly removes them.

Do not discard unrelated work, rewrite history, force-push, or perform destructive cleanup. Keep changes small and reviewable.

## Cross-project UX, DX, and AX principles

Cut taglines, helper text and secondary labels. If a screen needs them to make sense, fix the layout.

Make the best decision that will elevate all three: the user experience (UX), developer experience (DX), and agent experience (AX) always, without breaking anything.
