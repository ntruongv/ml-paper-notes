# ML Paper Notes

Personal notes on machine learning papers.

## Structure

- `papers/` contains one folder per paper, grouped by year.
- `topics/` contains hand-curated indexes across papers.
- `reading-lists/` tracks what to read next and what was especially useful.
- `templates/` contains reusable note templates.

## Paper Folder Convention

Use this pattern:

```text
papers/<year>/<paper-name>/note.md
```

Example:

```text
papers/2017/attention-is-all-you-need/note.md
```

Put screenshots, diagrams, or local figures for a paper in an `assets/` folder beside that paper's `note.md`.

## Workflow

1. Add a paper to `reading-lists/queue.md`.
2. Copy `templates/paper-note.md` into the appropriate `papers/<year>/<paper-slug>/note.md`.
3. Add topic links in `topics/` after the note has a stable takeaway.
4. Promote especially useful papers to `reading-lists/favorites.md`.

