# Gute Orte in Bergisch Gladbach und Umgebung

→ [hier öffnen](https://oshua-o.github.io/gute-orte/)

Du möchtest Orte beitragen? Melde Dich gerne bei der [Initiative KlimaGerecht Leben](mailto:initiative@klimagerecht-leben.de) und beschreibe die Orte, die Du hinzufügen möchtest mit Name, Beschreibung, Koordinaten und Adresse. Bitte beachte, dass nicht jeder eingereichte Ort sofort eingetragen werden kann.

## Einbetten mit iframe

Direkt aus github, Breite und Höhe entsprechend beliebig anpassen:
```html
<iframe
  src="https://oshua-o.github.io/gute-orte/index.html"
  width="800px"
  height="600px"
  style="border: none; border-radius: 8px;">
</iframe>
```


## Direkt einbauen

**1. In den `<head>` kopieren:**
```html
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" crossorigin=""/>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet.fullscreen/3.0.2/Control.FullScreen.min.css" crossorigin="">
<meta name="referrer" content="origin">
```

**2. An den Ziel-Ort im `<body>` kopieren:**
```html
<div id="map" style="width: 100%; height: 500px;"></div>
```

**3. An Ende von `<body>`:**
```html
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js" crossorigin=""></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet.fullscreen/3.0.2/Control.FullScreen.min.js" crossorigin=""></script>
<!-- hier den gesamten <script>-Block einfügen inkl. Design, Kategorien, Orte -->
```

## Lizenz

Kartendaten © [OpenStreetMap](https://www.openstreetmap.org/copyright) - Mitwirkende 

Gute Orte: [CC 0](https://creativecommons.org/publicdomain/zero/1.0/deed.de)
