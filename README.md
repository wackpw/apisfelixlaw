# ApisFelixLaw.com

Production source for **apisfelixlaw.com** — Apis Felix Law (a trade name of Deseret Lawyers PLLC), a plaintiff-side personal-injury trial firm serving Nevada & Utah.

- **Hosting:** GitHub Pages (branch `main`, root), custom domain via `CNAME`, `.nojekyll` (no Jekyll processing).
- **Canonical source of truth:** Google Drive → `Apis Felix Law Marketing/Website/` (keep Drive and this repo in sync).
- **Staged content:** blog/resources drafts live in Drive `Website/resources-staged/` and are committed here only after attorney approval (YMYL rule: nothing publishes without Kevin Peterson's sign-off).
- **Deploy quirk:** the built-in `pages-build-deployment` workflow intermittently fails at the `deploy` step ("try again later") and **re-runs tend to stall in Queued**. Fix: push any fresh commit — fresh runs deploy reliably.
- **Analytics:** GA4 loader in `index.html` is inert until `AFL_GA4_ID` is set to the real Measurement ID.

Compliance rails (NV/UT attorney advertising): no superlatives or guarantees; results/reviews sections stay hidden until verified; footer disclaimer required on every page.

## Milestones
- 2026-07-04: /resources/ hub + all 12 attorney-approved guides published (commit da9c83a); GA4 active (G-L7LEM1WDLV).
- 2026-07-05: /locations/ hub + 8 city-practice + 2 /es pages live; sitemap 26 URLs; GSC verified + sitemap submitted; GA4 firing.
