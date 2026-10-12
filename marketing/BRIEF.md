# Pirate RSS - marketing brief

Written for a marketing agent that has to work without asking questions. Facts below come from the Play listing, the app repo and the owner's decisions. Where something is not verified it says so.

## One line

Pirate RSS is a free Android RSS reader: all the sites you like in one clean feed, with a morning digest, read aloud and translation.

Store tagline: "All your sites in one clean feed. Read, translate and listen."
Name: "Pirate RSS" in every language (the owner decided to keep it, 2026-09-28).

## Links

- Play Store (live, version 3.0, versionCode 52, 178 countries): https://play.google.com/store/apps/details?id=com.yoyo.rss
- Privacy policy: https://yohaybn.github.io/open/privacy/
- Account deletion page: https://yohaybn.github.io/open/delete-account/
- Landing page: https://yohaybn.github.io/open/ is NOT a landing page right now. It returns 404. That path only hosts app-link pages (article, feed) and the policy pages. There is no marketing site yet. Use the Play Store link as the main call to action until one exists.
- Support: yohaybn@gmail.com
- Package id: com.yoyo.rss

## What the app does (as of 3.0)

- One feed for all sources: news sites and blogs, folders, source search and a discovery screen with catalogs (Israeli / international) and language and category filters.
- Clean reader: article text with images, dark and light themes, left-to-right and right-to-left support. Extraction works the same way for every site (no per-site hacks); if it fails, the page opens in a web view. Paywalled articles show a preview and a link, no bypass.
- Morning digest: a short summary of new articles from chosen sources. It uses the user's own Gemini API key (bring your own key). AI settings stay greyed out until a key is entered.
- Read aloud: listen to articles, auto-continue to the next one, control from the notification.
- Translation: translate a full article into the app language, offline (ML Kit language packs, about 30 MB each, Wi-Fi download by default) or with Gemini.
- Same story from several sources: an optional "smart scan" groups similar articles. It uses a small on-device model that is only downloaded if the user turns it on.
- Account backup: settings and saved articles back up to the cloud when signed in with Google. Guest mode works with local data only.
- Home-screen widgets: latest headlines from all feeds or from one chosen feed.
- Languages: Hebrew, English, Arabic, Russian.
- Free, with ads (Google Ads native cards). The listing says "The app contains ads."
- Requirements: Android 6.0 or newer. The 3.0 build is 64-bit (arm64) only; very old 32-bit phones stay on the previous version.

## Who it is for

- Primary: Hebrew-speaking Android users who follow Israeli news sites and blogs and want one calm feed. Hebrew and right-to-left are first-class, not an afterthought.
- Secondary: English, Arabic and Russian readers who want a simple RSS reader with translation and read-aloud.
- Typical people: commuters who listen to articles, people who read in a second language, people leaving a Feedly or Google-Reader-style habit who want a lighter app.

## Competitors and positioning

The owner uses Feeder as his reference competitor. Competitor feature claims below are general market knowledge, not re-checked on 2026-10-12. Verify before using any comparison in public copy.

- Feedly: the big cloud reader. Strong discovery, heavy paywalled AI. Pirate RSS positions as lighter and free, with the user's own AI key. Note: the app can load articles through Feedly's cloud, with a toggle to read original feeds only.
- Inoreader: powerful, rules and filters, subscription for advanced features. Pirate RSS is simpler.
- Feeder: open source, no ads, minimal. Closest rival. Pirate RSS differs by Hebrew/RTL focus, digest, read aloud and translation. Feeder has no ads and is open source; Pirate RSS has ads and is not.
- Others: NetNewsWire (not on Android), FreshRSS clients, Flym, Palabre. Not researched.

## Differentiators to lead with

1. Hebrew-first and RTL done properly, with Hebrew news sources easy to find.
2. Morning digest plus read aloud in one app: read, listen, skim.
3. Translation built in, offline option.
4. Privacy-minded design: no server of its own, AI runs with the user's key, optional on-device model, guest mode.
5. Clean pirate-parrot identity, light and dark themes.

Do not claim: "no ads", "open source", "no data collected", "works offline for everything". None is true. The Play Data safety form lists collected data (name, email, user IDs, crash logs, diagnostics, app interactions, other user content, device IDs) and says device IDs are shared for advertising. Say "privacy-minded" only with the privacy policy link beside it.

## Brand

- Mascot: pirate parrot with a tricorn hat that carries the RSS symbol. Icon is the parrot on navy.
- Palette: navy #0D2A4C, burgundy #5D1832, gold #CCA667, cream #F8F5EE. Alternative in-app themes: purple, blue-cream.
- Tone: friendly, calm, a little playful (pirate motifs, a mustache easter egg). No hype, no fear of missing out. The owner rejected new-article notifications on purpose.
- The loading spinner is a pipe with RSS smoke. The flat pirate illustrations (ship, parrot, hat, flag, compass, chest) appear only in the article player, never elsewhere.

## Assets in this folder

See README.md in this folder. Store icon and feature graphic are the live Play Console versions. Screenshots are the live listing, 1080x1920, five in English and five in Hebrew. They use sample articles (NASA images, fictional source names), so no real publisher content appears.

## Current state and constraints

- Version 3.0 went live on Google Play on 2026-10-12 (production, all 178 countries; 3 installs at the time of writing). There is no install base to quote and no ratings yet.
- Owner: one person. Support email above. Developer name on the Play page is a personal legal name; the owner wants "yo yo" used in marketing copy.
- Monetization: free with ads now. Possible later: voluntary support, a one-time ad removal. Do not promise either.
- Launch approach decided earlier: start with a small Hebrew audience, then widen.
- Money, store listing changes and account changes are the owner's decision. Do not publish, buy ads or change the Play listing without asking the owner.

## Suggested first work

1. Hebrew launch post and short video script using the screenshots (feed, reader, digest, models, drawer).
2. Hebrew communities where RSS and news readers are discussed (verify rules of each before posting).
3. A one-page landing site for yohaybn.github.io/open/ or a new domain, with the intro illustrations and the Play badge.
4. A short English version for r/androidapps style audiences.
