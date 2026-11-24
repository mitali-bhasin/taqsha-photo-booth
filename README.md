# Taqsha Air Photo Booth

A webcam photo booth for the Taqsha AI Residency demo day. One HTML file, no build step.

Live: https://mitali-bhasin.github.io/taqsha-photo-booth/

- `?fake=1` test pattern instead of the camera
- `?embed=1` camera only, for iframing into the deck (`allow="camera; autoplay"`)
- `?fx=warm|pop|mono|grain|fade|none` and `?cap=0..3` set the starting look and caption
- The deck can send `postMessage({type:'shoot'})` to fire the shutter

Photos never leave the browser. Nothing is uploaded.
