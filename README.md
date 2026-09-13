# Pictionary Air

A two-device browser drawing game. One player draws using touch or phone motion, while the drawing appears live on another screen through a six-digit room code.

## Play locally

Open `index.html` in a browser, or serve the folder with any static web server.

## Publish with GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then click **Save**.

The game uses PeerJS for real-time browser-to-browser communication. Phone motion access requires HTTPS, which GitHub Pages provides.
