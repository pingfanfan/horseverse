# Prompt

Build ONE single-file HTML (“Year of the Horse / 马年”) that runs by opening in a browser (no build). Inline all CSS/JS. NO external images/videos/fonts/models/textures/audio. Everything must be procedural (Canvas/SVG/WebGL).

Page: premium editorial, clean grid, cinematic. Palette: ivory #F6F1E7 + charcoal #111113 + red #C1121F + cyan #67D4C5. Add subtle grain/fog/parallax.

Must include:
1) HERO fullscreen: animated procedural “gallop/stampede vibe”, title “马年 · HORSEVERSE”, CN/EN toggle, CTA scrolls to gallery.
2) GALLERY: 10 styles of horses, each is a live-rendered card (Canvas/SVG/WebGL) + 1–2 small knobs (e.g., stroke, density, glitch) + short CN/EN caption. Include “Random Style”.
   Styles (use these 10): 水墨 ink wash, Ukiyo-e, Bauhaus geometric, Neon cyberpunk, Pixel art, ASCII, Paper-cut 剪纸, Clay/toon, Blueprint technical drawing, Generative line hatching.
3) FEATURED 3D: one real WebGL/WebGL2 horse scene (procedural mesh, clearly horse-like: body/head/neck/legs). Drag to rotate (inertia), wheel/pinch zoom, sun+ambient lighting, fog/atmospheric perspective, fake shadow ok.
4) COMPARE mode: split screen (left/right) to compare any two styles with synced time/rotation.
5) POSTER export: button exports current style as PNG; 3 presets: Minimal / Festival / Gallery Label.
6) Performance: small FPS indicator + “Low Power Mode” toggle to reduce effects.

Engineering: semantic HTML, accessible controls + modal help (“?” hotkey), smooth scrolling + subtle magnetic cursor on CTA and style pills, keep animation loops efficient (avoid allocations).

Output ONLY the final complete HTML in one code block.
