# g05_project
Projektbeschreibung "Karte der unentdeckten Orte"

Das Ziel ist es eine interaktive Karte zu erstellen, die in Wien spannende Orte abseits der normalen Wege der StadtbewohnerInnen und BesucherInnen beinhalten.
Ein Beispiel für so einen Ort ist das schmalste Haus Wiens hinter dem Museumsquartier oder der vergessene Bunker im Herrenholz. Diese können von den NutzerInnen interaktiv eingetragen werden.

Verwendete Layer wären:
- Grundkarte von OpenStreetMap
- ÖV-Stationen
- ÖV-Linien
- City-Bike-Stationen
- Radwegenetz
- WLAN-Hotspot-Karte
- Unser Layer mit den Punkten der "unentdeckten Orte"
- Optionaler Layer für "geheime Durchgänge"

Aufbau des Layer "unentdeckte Orte":
- Typ: Punkt
- Attribute: Name, Position, Kategorie, Beschreibung, (optional Bild mit automatischer Verkleinerung)
