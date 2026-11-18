# Margin

Margin is a React + Vite application for creating and formatting research papers in an IEEE conference style. It provides a structured alternative to manually assembling document layouts, sections, metadata, references, and academic content.

## Features

- Structured research paper editor
- Section and subsection management with automatic numbering
- Nested sections with drag-and-drop reordering
- Multiple authors and affiliations
- Abstract layout options: `full-width` and `two-columns`
- KaTeX equation editing and preview
- Figures, tables, lists, charts, and references
- Local autosave and draft recovery
- IEEE-style paper preview
- PDF export
- Editable Word (`.docx`) export

## Tech Stack

- React and React DOM
- Vite
- JavaScript
- `docx` for Word export
- `html2canvas` and `jspdf` for PDF-related rendering and export
- `katex` for equations
- `lucide-react` for icons
- `recharts` for chart rendering

## Getting Started

### Prerequisites

- Node.js and npm
- A modern web browser

### Install and run

```bash
git clone https://github.com/shaguntyagi136/Research-paper-formatter
cd Research-paper-formatter
npm install
npm run dev
```

Open the local URL shown by Vite in your browser.

## How to Use

1. Enter the paper title, authors, affiliations, abstract, and keywords.
2. Add or edit sections and subsections in the editor.
3. Use the section controls and drag-and-drop ordering to arrange the paper structure.
4. Add supported content such as paragraphs, lists, equations, figures, tables, charts, and references.
5. Choose the preferred abstract layout and use Preview to review the IEEE-style document.
6. Export the current paper as PDF or as an editable Word document.

Drafts are saved locally in the browser and can be recovered when the application is reopened in the same browser profile.

## Current Status and Roadmap

### Implemented

- Structured paper editing and nested section management
- Author and affiliation metadata
- Abstract layout selection
- Equations, figures, tables, lists, charts, and references
- Local draft persistence
- Preview, PDF export, and Word export

### Roadmap and verification

- Continue improving PDF and Word layout fidelity against official IEEE templates.
- Verify pagination, column flow, equations, images, charts, tables, and long metadata across browsers and Word versions.
- Add broader export coverage and automated output checks.

IEEE-style formatting is an editing and presentation goal; this project does not guarantee publication compliance with every IEEE venue or submission requirement.

## Contributing

Use GitHub Issues to report reproducible bugs or suggest improvements. For code contributions, fork the repository, create a focused branch, make the change, and open a pull request with a clear description of the behavior changed.

## License

No license has been specified for this repository yet.
