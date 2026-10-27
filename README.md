# maible-site

Statische Website von maible (16 Seiten, Variante „v3“ aus dem Claude-Design-Canvas).
Wird direkt über GitHub Pages ausgeliefert, ohne Webflow.

Bearbeiten: Datei ändern → committen/pushen → nach ca. 1 Minute live.

## Aufbau
- Jede Seite ist eine eigene HTML-Datei im Hauptordner (`index.html` = Startseite).
- Links zwischen den Seiten sind ohne `.html` geschrieben (z. B. `fireworks`). GitHub Pages löst das automatisch auf.
- Bilder und Schriften liegen in `assets/`.
- CSS steht jeweils im `<head>` der Seite, das Seitenskript am Ende von `<body>`.

## Seiten
| Datei | Seite |
|---|---|
| index.html | Startseite |
| fireworks.html | FIREworks |
| anwendungen.html | Anwendungen |
| scribe.html | Scribe |
| spark.html | Spark |
| smoke.html | Smoke |
| sicherheit.html | Sicherheit |
| entwickler.html | Partner / Entwickler |
| fallstudien.html | Fallstudien |
| fallstudie-umm.html | Fallstudie UMM |
| ueber-uns.html | Über uns |
| advisory-board.html | Advisory Board |
| von-myscribe-zu-maible.html | Von myScribe zu maible |
| faq.html | FAQ |
| impressum.html | Impressum |
| datenschutz.html | Datenschutz |

## Offen vor dem Livegang
- Platzhaltertexte („Lorem ipsum“) ersetzen: Startseite (Testimonials), Fallstudie UMM, Spark, Smoke, FIREworks, Scribe, Fallstudien, Advisory Board.
- Cookie-Banner: Die Seite setzt keine Cookies und hat kein Tracking. Banner entfernen oder Text anpassen.
- Datenschutzerklärung um den Hoster (GitHub Pages) ergänzen.
