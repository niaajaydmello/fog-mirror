# fog mirror

A self-contained browser experiment that turns your webcam into a fogged bathroom mirror.

- Breathe toward the microphone to build fog.
- Pinch thumb and index finger to draw through it.
- Make a fist and swipe to wipe a wide area.
- Hold **Space** to fog silently, press **C** to clear, **S** or the shutter button to save a PNG, and **Esc** to return to the start screen.

## Run it

`getUserMedia` requires a secure context. Serve this folder from `localhost` (or HTTPS), for example:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/fog.html> and click **step into the mirror**.

The camera and microphone stay in the browser. No frames, audio, or data are uploaded.
