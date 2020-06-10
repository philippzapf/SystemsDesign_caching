# SystemsDesign_caching
Kleines Code Beispiel auf dem localhost:3001, der zeigt, dass eine Seite mit Cache schneller lädt als eine Seite ohne Cache

## Schritt 1
Öffne das Terminal, navigiere in den Ordner mit den Files, tippe ... node server.js

## Schritt 2
Öffne Chrome und tippe http://localhost:3001/nocache/index.html, beobachte die Dauer bis "Hello World" erscheint

## Schritt 3
Tippe anschließend http://localhost:3001/withcache/index.html und aktualisiere es ein paar Mal. Beobachte wie es beim Ersten Mal, genauso lange gedauert hat, wie mit nocache. Anschliessend ist es jedoch direkt erschienen

## Fazit
Caching ist ein gutes Mittel, um den Clients Inhalte schneller zu präsentieren. Jedoch ist dabei zu beachten, wo der Cache platziert wird (Client, Server, Database oder irgendwo dazwischen) und in welchem Rythmus er synchronisiert wird mit.
