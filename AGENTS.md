# thikander.github.io: handoff for agents

This is the personal profile page of Theerapat Pinkrajan (GitHub `thikander`), served from `main` at https://thikander.github.io/.

- **Page:** `index.html` is one static page with no build step. It is low-res pixel style on a white background, uses the Pixelify Sans font (Google Fonts), and draws its pictures on canvases with hard pixel borders and shadows.
- **Layout:** like a Facebook profile:
  - an animated pixel cover scene (sky, hills, road, a little car)
  - the name "Theerapat Pinkrajan", `@thikander`, and a project count
  - a GitHub button
  - a "Collection" grid
- **Collection:**
  - The first tile is **Tiny Turbo** (`tiny-turbo/`, repo `thikander/tiny-turbo`), with a 32×32 cluster icon drawn on canvas and a tiny mochi on top. Hovering sweeps the needle and makes the mochi hop.
  - The other tiles are dashed "?" placeholders. To add a project, replace a placeholder with a new `<a class="item">` and update the counts (`#count`, the tab number).
- **Owner preferences:**
  - Show the owner the page **before committing** changes here.
  - Don't add their photo or avatar back; they asked to remove it.
  - Only their name is shown as profile info.
- **Domain:** `page.thikander.cyou` expired and was removed (no CNAME file). Don't add it back unless the owner renews the domain.
- **Unused asset:** `assets/main_profile.png` isn't used by the page. The owner hasn't decided whether to delete it.
- **Shipping:** push to `main`, then wait until `gh api repos/thikander/thikander.github.io/pages/builds/latest` reports `built <sha>`.

The full system notes for the game are in the Tiny Turbo repo's `AGENTS.md`.
