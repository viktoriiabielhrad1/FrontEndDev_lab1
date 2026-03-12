# project1

1) Stage 1 — Basic HTML Structure Completed
Both index.html and characters.html were created using clean semantic HTML5. Each page includes headings, paragraphs, and basic content with no CSS, no images, and no navigation. The structure validates correctly and forms the foundation for later stages.

2) Stage 2 — Images Added
Local images were added to both pages using meaningful alt text. Images are placed in logical sections (e.g., character portraits on the characters page). No styling was applied yet, keeping the layout intentionally plain.

3) Stage 3 — Navigation Links Added
A simple <nav> section was added to both pages, allowing users to move between Home and Characters. Links use relative paths and work correctly across the two-page structure.

4) Stage 4 — CSS Styling Implemented
A dedicated CSS file was created and linked to both pages. Layout, typography, colors, spacing, and image presentation were styled to match the provided screenshots. The navigation bar and overall page design now resemble the expected final look for the static version.

5) Stage 5 — Refactored into SvelteKit Project
The entire site was rebuilt as a SvelteKit project.
Reusable components were implemented, including:

NavBar.svelte — shared navigation across all pages

Footer.svelte — includes a short confirmation message noting completion of all stages

Pages were moved into SvelteKit’s routing structure (/src/routes/), and components were imported cleanly.
