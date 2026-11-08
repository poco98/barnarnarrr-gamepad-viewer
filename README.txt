BARNARNARRRR — MIDNIGHT / BANANA STUDIO EDITION — V2

New midnight-navy artwork, warm banana-yellow side rails, porcelain controls,
and a custom banana emblem inspired by the channel's public banana/arcade
branding. The emblem is an original interpretation, not an official logo.
Channel reference: https://www.twitch.tv/barnarnarrrr/about
All visible labels and documentation are in English.

OBS INSTALLATION
Keep your Xbox One Gamepad Viewer Browser source and player URL. Set the
source to 750 × 630. Copy ALL of barnarnarrrr-obs.css into the OBS source
Custom CSS field. Refresh the source and press a controller button.
All graphics are embedded; no separate images or hosting are required.

EXTERNAL CSS
Host edit.css, all nine .svgz files, and the assets folder together on HTTPS.
Use Edit CSS URL, or host the self-contained barnarnarrrr-obs.css on its own.
The .svgz files contain plain SVG, as in the original pack: serve them as
image/svg+xml without a gzip Content-Encoding header. This pack is not hosted.

PREVIEW
Open preview.html for Idle, Active inputs, Demo, Xbox / Guide, Disconnected,
and Live controller. Z/X/C/V = A/B/X/Y; arrows = D-pad; Q/E = LB/RB;
R/T = LT/RT; G = Xbox / Guide. You can also click the logo and controls.
For physical input use a Gamepad API browser on localhost or HTTPS.
With Python installed, run from this folder:
  python -m http.server 8765 --bind 127.0.0.1
Then open http://127.0.0.1:8765/preview.html and press a controller button.
Gamepad Viewer retains its own detection, player selection, and remapping.

XBOX / GUIDE LIGHT
The banana emblem illuminates amber while Xbox / Guide is held and returns
to its idle finish on release. The CSS responds to .meta.pressed, which is
the current GPV Xbox One Guide control. The page must receive that input;
an OS or application that intercepts Guide may prevent it reaching GPV.
No physical Xbox/Guide button or OBS source was tested for this revision.

FILES
barnarnarrrr-obs.css: self-contained OBS skin.
edit.css + *.svgz + assets/: external-asset version and editable sources.
assets/banana-mark.svg and banana-mark-active.svg: channel-inspired emblem.
Preview*.svg / .png: idle, inputs active, Guide held, and disconnected.
Presentation.png / .svg: full-body overview. Logo-glow.png / .svg: light detail.
CHANGES.md, VALIDATION.md, manifest.json: notes and verification.
LICENSE.txt: original Dracula Theme MIT license, retained unchanged.

V2 CLEANUP
Removed the decorative four-block row from the lower shell.
The functional player indicator near the center buttons is unchanged.
