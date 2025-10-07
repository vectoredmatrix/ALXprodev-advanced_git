🪝 Git Hooks Setup

This repository includes custom Git hooks to automate checks and logs during development.

🔹 Pre-Commit Hook

File: .git/hooks/pre-commit

Purpose: Ensures every directory contains a README.md file before allowing a commit.

Behavior:

Aborts the commit if any folder is missing README.md.

Shows a clear error message.

🔹 Post-Merge Hook

File: .git/hooks/post-merge

Purpose: Logs every successful merge into the main branch.

Behavior:

Appends merge info (with date) to merge_log.txt.
