# Notes viewer

The built viewer for [Notes](https://github.com/versaion) — a system in which an LLM
authors rich, interactive pages, and this program renders them in the browser.

This repository holds **only the built artifact**. It is generated, and pull requests against it
will not be read. Pages are never built into it: it fetches a page's source over HTTP from
wherever that page is served and compiles it in the tab.

    <script type="module" src="https://versaion.github.io/notes-viewer/v1/notes.js"></script>

`v1` is updated in place and revalidated rather than cached forever. A new number would
mean a genuinely breaking change.
