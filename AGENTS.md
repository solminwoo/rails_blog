# rails_blog engineering guidance

<!-- ecc-engineering-defaults:start -->
## Engineering defaults
For coding work, read [.engineering/defaults.md](.engineering/defaults.md).
These are shared fallback conventions; the existing project owner, nested instructions,
skills, model choices, domain contracts and stronger verification/release gates remain authoritative.
No hooks, permissions, MCP services or background automation are installed by this guidance.

### Project adaptation
Rails 6.1 / Ruby 2.7.2 with Gemfile.lock and yarn.lock. Candidate check: `bundle exec rails test` using an isolated test database after inspecting test setup. Preserve migrations and existing frontend tooling; no production migrations or deployment from routine verification.
<!-- ecc-engineering-defaults:end -->
