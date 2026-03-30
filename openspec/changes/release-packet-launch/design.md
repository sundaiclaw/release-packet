# Design: Release Packet Launch

## Context
The product should feel like a launch war-room assistant, not a generic text generator. The MVP should make it easy to drop in messy material and instantly get structured outputs that feel credible.

## Decisions
- Use a Node/Express single-page app for fast shipping.
- Keep user input as a multi-field form with seeded sample content.
- Make AI the core value by generating multiple launch artifacts from the same messy input.
- Preserve useful fallback behavior if the AI key is unavailable.
