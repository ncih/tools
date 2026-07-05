# tools.nicholaschong.xyz

Small owned tools, one GitHub Pages site. **Each subfolder is a tool**, served at
`tools.nicholaschong.xyz/<folder>/`.

| Tool | Path | Live |
|---|---|---|
| Presenter Kit | `presenter-kit/` | https://tools.nicholaschong.xyz/presenter-kit/deck.html |

## Convention
- One subfolder per tool. Relative links inside a tool stay relative, so a tool works the
  same locally and under its `/<folder>/` path.
- `CNAME` (= `tools.nicholaschong.xyz`) and an empty `.nojekyll` live at the **repo root**,
  not inside a tool folder. `.nojekyll` stops GitHub Pages running Jekyll (which 404s the
  JS-brace-heavy HTML here).
- Add a tool: drop its folder in, add a row above, push. It's live at
  `tools.nicholaschong.xyz/<folder>/`.
- Future sibling categories get their own repo + subdomain the same way (`labs.`, `slides.`, …).
