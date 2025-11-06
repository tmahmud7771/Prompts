````markdown
# Figma Section Build Guide

Run this command to connect the Figma MCP Server to Claude:
```bash
claude mcp add --transport sse figma-dev-mode-mcp-server http://127.0.0.1:3845/sse
````

Section Name: [SectionName]
Figma Link: [SectionLink]

---

### Instructions

* Build this section using **Next.js** and **Tailwind CSS**.
* Save the code inside:

  ```
  components/[SECTION_FOLDER_NAME]
  ```

  Example:

  ```
  components/hero
  components/faq
  components/products
  components/blog
  ```
* Import and render this section inside:

  ```
  app/page.js
  ```

---

### Guidelines

* Use random placeholder images:

  * [https://picsum.photos/400/300](https://picsum.photos/400/300)
  * [https://picsum.photos/1920/1080](https://picsum.photos/1920/1080)
* Use clean, semantic JSX and Tailwind classes for all styling.
* Keep the layout responsive for desktop, tablet, and mobile.
* If the section contains reusable parts (cards, buttons, text blocks), create smaller components inside the same folder (e.g., `Card.js`, `Button.js`).
* Do not hardcode text not visible in the Figma file — use placeholder text instead.
* Follow Next.js best practices:

  * Use `Image` from `next/image` for images
  * Use `Link` from `next/link` for navigation

```
```
