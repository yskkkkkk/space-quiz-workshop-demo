# Space Quiz Workshop Demo

A Korean-language space exploration quiz in one self-contained HTML file.
Open `index.html` in a modern browser. No server, installation, network
connection, or external dependencies are required.

## Features

- Ten questions, progress tracking, scoring, and answer explanations.
- Green correct-answer feedback and red shaking incorrect-answer feedback.
- Results with a score count-up, large emoji reactions, and restart.
- Read-only review of this run's incorrect answers, correct answers, and explanations.
- Keyboard navigation with Tab, Enter, and Space; screen reader announcements.
- Automatic light/dark themes and reduced-motion support.

## Workshop files

- `index.html`: all quiz markup, styles, JavaScript, and illustrations.
- `AGENTS.md`: project-specific development instructions.
- `.gitignore`: an explicit allowlist excluding unrelated local files.

Before publishing, review `git diff --cached` and confirm that only these
workshop files and this README are staged. Never force-add unrelated files,
credentials, local settings, business documents, or logs.
