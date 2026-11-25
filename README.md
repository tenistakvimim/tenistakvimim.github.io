# tenistakvimim.github.io

Home, privacy policy, support and team invite pages for Tenis Takvimim, an iOS app for tennis league team matches.

| | Home | Privacy | Support |
|---|---|---|---|
| Türkçe | [`/tr/`](https://tenistakvimim.github.io/tr/) | [Gizlilik Politikası](https://tenistakvimim.github.io/tr/privacy.html) | [Destek](https://tenistakvimim.github.io/tr/support.html) |

The root, [tenistakvimim.github.io](https://tenistakvimim.github.io/), forwards to `/tr/`.
Adding a language means adding one more `/<code>/` with `index.html`, `privacy.html`
and `support.html`, then linking it from the root.

## Team invites

`https://tenistakvimim.github.io/davet/?kod=CAN-1234` shows the team code and an
"open in app" button (`tenistakvimim://katil?kod=…`; `&dev=1` opens the dev build).
`.well-known/apple-app-site-association` already claims `/davet/*` so the link can
open the app directly once the app ships with the `applinks:tenistakvimim.github.io`
associated domain.

All pages share `site.css`. `.nojekyll` keeps `.well-known/` published.

Contact: kmertcansdev@gmail.com
