# 100 Jahre Blau-Gelb Frankfurt

Landing page für das 100-jährige Jubiläum des Vereins Blau-Gelb Frankfurt.

## 🚀 Live-Seite

Gehostet via **GitHub Pages** → `https://<dein-username>.github.io/<repo-name>`

## ✏️ Inhalt bearbeiten

Alle Inhalte befinden sich in einer einzigen Datei:

```
index.html   ← Hier alles bearbeiten
```

### Veranstaltungen anpassen

Suche im HTML nach den `<div class="event-card">` Blöcken und ändere:

- **Uhrzeit** → `<span class="time">17:00</span>`
- **Titel** → `<h3>Name der Veranstaltung</h3>`
- **Beschreibung** → `<p>Kurze Beschreibung...</p>`
- **Tag/Label** → `<span class="event-tag">Kategorie</span>`

### Neue Veranstaltung hinzufügen

Kopiere einen bestehenden `event-card` Block:

```html
<div class="event-card">
  <div class="event-time"><span class="time">HH:MM</span><span class="uhr">Uhr</span></div>
  <div class="event-body">
    <h3>Name der Veranstaltung</h3>
    <p>Kurze Beschreibung der Veranstaltung.</p>
    <span class="event-tag">Kategorie</span>
  </div>
</div>
```

## 🔧 GitHub Pages einrichten

1. Repository auf GitHub erstellen (öffentlich)
2. Code pushen: `git push origin main`
3. Auf GitHub: **Settings → Pages → Source: main branch / root**
4. Nach ~1 Minute ist die Seite live ✅
