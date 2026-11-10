PSR Computer Store - installable web app (PWA)

It must be served over HTTPS (or localhost) for the Install option to appear.

1) Put it online (free, pick one)
   - Netlify Drop: open app.netlify.com/drop and drag this whole folder onto the page.
   - GitHub Pages: upload these files to a repository, then Settings > Pages.
   - Vercel: "vercel" in this folder.
   Test on your laptop first: run "npx serve" in this folder and open http://localhost:3000

2) Install it
   - Android (Chrome): open the link > tap "Install" in the banner, or menu > Install app / Add to Home screen.
   - iPhone / iPad (Safari): Share button > Add to Home Screen.
   - Windows / Mac (Chrome or Edge): click the Install icon at the right end of the address bar.

Edit prices and products: open index.html, find "var P=[" and change p: (price) and o: (old price).
Updating: when you change index.html, change "psr-v1" in sw.js to "psr-v2" so phones get the new version.
