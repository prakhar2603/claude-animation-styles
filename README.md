# 10 animation styles Claude can make

Paste one of these into Claude (claude.ai or Claude Code), then add your own scene at the end, for example:
"My scene: Ganpati Bappa driving an auto-rickshaw through Mumbai at sunrise, his mouse on the roof holding a modak."
Claude writes the animation as an HTML page with SVG. Open it in your browser, or ask Claude to make it 1080x1920 for a reel.

Every style in the video was made this way, from one scene, with no image or video AI.

---

**1. Pixel Art**
Make an animated scene as a single HTML file with inline SVG, 1080x1920. Draw it with flat colours, no outlines, then
pixelate the whole thing with an SVG filter (feFlood + feTile + feComposite + feMorphology dilate) so it looks like
16-bit pixel art with chunky square pixels. Limited palette: deep blue sky fading to orange, warm window lights.
Loop the motion smoothly. My scene:

**2. Chalkboard**
Make an animated scene as a single HTML file with inline SVG, 1080x1920, drawn like chalk on a green school
blackboard (#24402F) with a wooden frame. Only outlines in white and soft pastel chalk colours, with light diagonal
hatching inside big shapes. Roughen every line with an feTurbulence + feDisplacementMap filter so it looks hand-drawn,
add faint chalk-dust smudges and a handwritten title, and animate every line drawing itself on (stroke-dashoffset)
before things start to move. My scene:

**3. Line Art**
Make an animated scene as a single HTML file with inline SVG, 1080x1920, on a near-black warm background with a soft
spotlight beam falling from the top and a warm glow on the floor. Draw everything as thin coloured outlines (each
object keeps its own colour), closed shapes filled with the background so lines behind them are hidden, and a faint
glow on the lines. Lines draw themselves on first, then the scene moves. My scene:

**4. PS2 3D**
Make an animated scene as a single HTML file, 1080x1920, that looks like an early-2000s PlayStation 2 game. Split the
scene into 4 SVG layers (sky, buildings, road, the main subject) stacked in CSS 3D (preserve-3d, different
translateZ) and slowly orbit the camera. Make round things low-poly (6 or 7 sided), give every shape hard banded
shading with an SVG lighting filter (feDiffuseLighting + feComponentTransfer discrete), add distance fog, and render
it slightly low-res with a small pixelate filter. My scene:

**5. Comic Book**
Make an animated scene as a single HTML file with inline SVG, 1080x1920, in pop-art comic style: bright flat
colours, thick black outlines on every shape, a halftone dot pattern over the sky, speed lines, and a comic burst with
a sound word that pops in. My scene:

**6. Flat Vector**
Make an animated scene as a single HTML file with inline SVG, 1080x1920, in clean modern flat vector style: no
outlines, a soft gradient sky with sun rays, a friendly palette, simple geometric shapes with a lit side and a shaded
side, light film grain. Smooth, looping motion. My scene:

**7. Gold Line Art**
Make an animated scene as a single HTML file with inline SVG, 1080x1920, as minimal luxury line art on a pure black
background: only the main subject, the ground line and the sun as thin concentric rings, all in thin gold (#D4AF37)
lines with a soft gold glow. Nothing else in the frame. Every line draws itself on slowly. My scene:

**8. 3D CGI**
Make an animated scene as a single HTML file, 1080x1920, that looks like a soft 3D animated film. Split the scene into
4 SVG layers (sky, buildings, road, the main subject) stacked in CSS 3D (preserve-3d, different translateZ) and move
the camera slowly around them. Blur the far layers for depth of field (CSS filter: blur), give every shape soft
rounded lighting (feSpecularLighting) and a soft shadow, and add a warm colour grade on top. My scene:

**9. Lego Style**
Make an animated scene as a single HTML file with inline SVG, 1080x1920, built like LEGO bricks: classic LEGO colours
(red, blue, yellow, green, grey), round studs on the top edge of every block, brick seams on walls, a grey baseplate
with a stud pattern for the ground, and a glossy plastic look from an SVG lighting filter with a small drop shadow.
My scene:

**10. Clay 3D**
Make an animated scene as a single HTML file with inline SVG, 1080x1920, that looks like soft clay or plasticine:
pastel colours and an SVG lighting filter (feGaussianBlur on the alpha + feSpecularLighting) on every shape so it
looks rounded and shiny like modelling clay, slightly lumpy edges (feDisplacementMap), and soft shadows underneath.
My scene:
