# Ascendant Labs

Website for **Ascendant Labs**, an independent app studio. *Imagine. Create. Ascend.*

**Live:** https://tharunvetcha.github.io/ascendantlabs/

## Pages

| Page | URL |
| --- | --- |
| Ascendant Labs (studio) | https://tharunvetcha.github.io/ascendantlabs/ |
| Self Chat (app) | https://tharunvetcha.github.io/ascendantlabs/selfchat/ |
| Self Chat privacy policy | https://tharunvetcha.github.io/ascendantlabs-policies/self-chat/ (in [ascendantlabs-policies](https://github.com/tharunvetcha/ascendantlabs-policies)) |
| Self Chat on Google Play | https://play.google.com/store/apps/details?id=com.selfchat.app |

## Structure

```
index.html              Studio site (single page, inline CSS/JS)
404.html                Not-found page
selfchat/index.html     Self Chat app site
selfchat/img/           Self Chat icon and share image
assets/                 Logos (incl. 512px originals) and share image
favicon.ico, favicon.png, apple-touch-icon.png
sitemap.xml             Submitted to Google Search Console
.nojekyll               Serve files as-is (skip Jekyll)
```

Plain HTML/CSS with no build step. Light and dark themes follow the device setting, with a toggle that remembers the visitor's choice across both sites.

## Publishing

Served by GitHub Pages from the `main` branch, root folder. Changes go live a minute or two after merging to `main`.

## Contact

hello.ascendantlabs@gmail.com
