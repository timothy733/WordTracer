# WordTracer

*A structural Bible study tool*

**[Try it live](https://timothy733.github.io/WordTracer/)** · [License: GPLv3](LICENSE) · [Feedback & Discussions](https://github.com/timothy733/WordTracer/discussions)

## What it is

WordTracer helps you slow down over a Bible passage and trace its structure — dividing the text into its units of thought, nesting subordinate ideas under main ones, colour-coding chunks, and attaching notes to individual words. The words never change, because every word is given by God — down to the conjunctions that carry the argument. Your task is not to impose a structure but to discern the one the author built, so that in following his flow of thought you hear the intention of the human author, and in it, the voice of the divine Author.

The scripture text is read-only from the moment you import it. Everything you do afterward — splitting, indenting, titling, colouring, annotating — is a layer of interpretation built *on top of* the text, never a change to it.

## Getting started

WordTracer is a single, self-contained HTML file — nothing to install, no account, no server. Open the [live version](https://timothy733.github.io/WordTracer/) in any modern browser, desktop or mobile, paste in a passage, and start structuring.

A saved study is also fully self-contained: saving embeds your work directly into a complete copy of the app as one `.html` file, so opening it again later — on any device, offline — picks up exactly where you left off.

## Usage guide

### Splitting a passage into chunks

- Long-press (or click-and-hold) any word to arm the cursor there.
- Tap or click any other word to jump the cursor to it directly.
- In the cursor bar, use **←** / **→** to step one word at a time. On desktop, the arrow keys do the same, and **↑ / ↓** jump to the nearest word on the visual line above or below.
- Press **SPLIT** (or **Enter** on desktop) to divide the passage at the cursor into two independent chunks. **Cancel** (or **Escape**) backs out without changing anything.

### Indenting chunks

- Tap a chunk to select it — the context bar appears at the bottom.
- **← Outdent** and **Indent →** change that one chunk’s own indent level.
- Indentation is purely a visual position on the page. It does not create ownership or hierarchy between chunks — two chunks at different indents are still fully independent, and nothing done to one ever affects another.
- On desktop: **Shift + ←/→** do the same as the buttons; plain **↑ / ↓** (no Shift) moves the *selection itself* to the chunk above or below.
- **Merge ↓** joins a chunk with the very next one in reading order, regardless of either one’s indent level.

### Chunk titles

- With a chunk selected, tap **Details** to open its detail pane, which includes a title field.
- On desktop: press **T** to jump straight into the title field, or **Space** to open the pane without focusing anything — useful for just checking or changing a colour.
- A title renders as a small heading above its chunk. It’s a label for that one chunk only — it never implies ownership over whatever happens to be indented beneath it.

### Word notes

- Long-press a word to arm the cursor on it, then tap **Note** (or press **Space** on desktop).
- A full-screen dialog opens showing the word in its sentence for context, with the text field ready to type into immediately.
- A noted word gets a small underline in the outline. Notes stay attached to their exact word even if the surrounding chunk is later split or merged.

### Chunk colouring

- Open a chunk’s **Details** pane and pick a colour swatch.
- The eight colours match Microsoft Word’s own standard palette — familiar if you’ve ever colour-coded a Word document.
- Colour belongs to that one chunk only. Colouring a chunk never changes any other chunk’s colour, at any indent level.

### Reading view

- Tap the notepad icon (🗒) in the toolbar for a clean, fully static rendering of your structure — headings, indentation, colour, and every word note shown inline — with nothing clickable except a font-size control.
- Meant for actually reading back through what you’ve built, or for printing, rather than for further editing.

## Other things worth knowing

- **Verse numbers** — any bare number in pasted text is automatically detected and rendered as a small superscript attached to the following word. Toggle visibility with the **¹** button in the toolbar; Reading view always shows verse numbers regardless of that toggle.
- **Multiple structures** — build more than one independent outline of the same passage (for example, one for preaching and one for personal study) and switch between them from the toolbar.
- **Search** — find a word, or search inside your notes, from the toolbar search field.
- **Three appearances** — Console, Modern Light, and Modern Dark (the default). Cycle through them with the ◐ button.
- **Undo/redo**, full desktop keyboard support, and a Markdown export are all built in.

## Saving and loading

- **Save** embeds your current study directly into a complete copy of the app as one `.html` file. Opening that file again later — on any device, with no internet connection required — picks up exactly where you left off.
- **Loading an older save** into a newer version of the app asks for confirmation first, since a version gap means the automatic upgrade hasn’t been verified against every case. Your original file is never altered by this.
- **Loading a newer save** into an older version of the app is declined outright — there’s no reliable way to guess at a format the app doesn’t yet know about.

## License

WordTracer is free software, licensed under the [GNU General Public License v3.0](LICENSE). You’re free to use, study, modify, and redistribute it, provided any distributed modification stays under the same license.

## Feedback

Questions, bug reports, or ideas are welcome — please [open a GitHub Discussion](https://github.com/timothy733/WordTracer/discussions) rather than emailing directly.


<meta name="google-site-verification" content="8BC2sk4oYjn4bwFoUw2gLviFzD5wTFVG2oqWTyvjf2c" />
