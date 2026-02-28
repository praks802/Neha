# Dancing Reel (single-page)

This page now does both:

1. **Live dancing preview** of your uploaded image.
2. **Actual reel export** as a downloadable `.webm` video.

## Open it

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/dancing_reel.html`.

## Use it

1. Click **Upload Picture** and choose your image.
2. Preview runs automatically in a 9:16 frame.
3. Click **Create 6s Reel (WebM)**.
4. Wait a few seconds, then click **Download Reel**.

## Time to create a reel

- Typical creation time is about **6–12 seconds** on most laptops/desktops (6 seconds content + encoding overhead).
- Slower devices/browsers may take longer.
