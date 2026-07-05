# SEO- & GEO-Audit — norbert-pohlmann.com (Glossar Cyber-Sicherheit)

Professionell aufbereitete Ergebnisseite des SEO- und GEO-Audits für
[https://norbert-pohlmann.com/glossar-cyber-sicherheit/cyber-sicherheit-2/](https://norbert-pohlmann.com/glossar-cyber-sicherheit/cyber-sicherheit-2/)

**Live-Seite:** https://mohammadalboush.github.io/analyse/

## Inhalt

- `index.html` — interaktive Ergebnisseite (eine HTML-Datei)
- `evidence/` — alle Original-Nachweise:
  - PageSpeed Insights Desktop & Mobile (PDF)
  - Otterly.AI Crawlability-Audit, Content-Analyse, Brand-Report (PDF)
  - 10 Screaming-Frog-Screenshots + Otterly Server Access Check + llms.txt-Original

## Datengrundlage (Erhebung: 05.07.2026)

| Quelle | Umfang |
|---|---|
| Google PageSpeed Insights (Lighthouse 13.4.0) | Desktop 98/80/100/83 · Mobile 82/84/92/83 |
| Screaming Frog SEO Spider | 456 URLs · 1 Fehler / 17 Warnungen / 17 Gelegenheiten |
| Otterly.AI | Crawlability (21 KI-Crawler), Content-Readiness, Brand-Report |
| Eigene Live-Verifikation | robots.txt, llms.txt, Glossar- & Startseite |

## Kernbefund

Alle 21 geprüften KI-Crawler (GPTBot, ClaudeBot, PerplexityBot …) werden auf
Server-/Firewall-Ebene blockiert, obwohl die robots.txt sie per `Allow: /` freigibt.
Details, Nachweise und der priorisierte 12-Punkte-Maßnahmenplan: siehe Live-Seite.
