# Business English Notes

[Live site](https://business-english-notes.vercel.app)

A minimal Korean business English vocabulary notebook with exactly 1,000 words and short business expressions.

- Four columns: English term, Korean meaning, short English example, checkbox.
- Checked terms move to the end in the order checked. Unchecking restores the original learning order.
- Progress is saved in this browser using localStorage, including across reloads. It is not synced between devices.
- Narrow examples scroll within their cells so the entire page stays within the viewport.
- No external libraries, fonts, images, accounts, tracking, or build step.

The complete site is authored in `dist/index.html`, including its vocabulary JSON, styles, and JavaScript. Vercel serves `dist` using `vercel.json`. 

Design reference: https://vfat.tools/ (checked September 6, 2026). The reference's light-mode CSS defines a #dddddd background, #272727 text, mediumseagreen highlights (#3cb371), and visited-link purple (#4b2f89). This site uses that light palette and a simple monospace table layout; it does not copy the reference's code or content.

Learning progress is a convenience, not a permanent account record. Clearing browser storage clears progress. Blocked storage is handled with a visible message while allowing the checklist to remain usable for the current visit.

The original 240 entry IDs and localStorage key remain unchanged when the list expands, so existing checks survive updates at the same site address. The additional 760 entries cover workplace communication, marketing, finance, sales, operations, management, and strategy.
