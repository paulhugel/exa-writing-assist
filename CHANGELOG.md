# Changelog
## [Unreleased]

- chore(config): Accepted Next.js auto-generated updates
  - Reformatted `tsconfig.json` (`"lib"` array multi-line)
  - Added `"target": "ES2017"` to support top-level `await`
  - Updated `next-env.d.ts` (Next.js environment types)
  
## [Unreleased]

## [2025-08-22]

### Added
- Expanded `.gitignore` with standard Next.js/Node.js entries.

### Changed
- Cleaned up `.env.example` formatting (left-justified all keys).
- Updated README.md to clarify API Keys configuration for Exa, Anthropic and OpenAI.

### Repository Maintenance
- Removed obsolete branch `chore/upgrade-next-15-4` (no upstream).
- Merged work back into `main` to keep repo clean and up-to-date.
- Verified sync between local and GitHub `main`.