# Branching Strategie

Für dieses Repository wird die **Feature Branching Strategie** verwendet.

## Beschreibung

Bei Feature Branching wird für jede neue Funktion oder Änderung ein eigener Branch erstellt. Dadurch bleibt der `main` Branch aktuell, funktionsfähig und enthält nur getesteten und funktionierenden Code.

Die Entwicklung neuer Features findet in separaten Branches statt. Sobald ein Feature fertig ist, wird es über einen Pull Request überprüft und anschließend in den `main` Branch gemerged.

## Workflow

1. Der `main` Branch enthält immer den stabilen Stand des Projekts.
2. Für neue Funktionen oder Änderungen wird ein neuer Branch erstellt (z.B. `feat/login` oder `feat/automatisierung`).
3. Die Entwicklung erfolgt im Feature Branch.
4. Nach Abschluss der Entwicklung wird ein Pull Request erstellt.
5. Nach Review und erfolgreichem Test wird der Branch in `main` gemerged.

## Vorteile

- Der `main` Branch bleibt stabil.
- Mehrere Entwickler können gleichzeitig an verschiedenen Features arbeiten.
- Änderungen sind klar voneinander getrennt.
- Pull Requests ermöglichen Code Reviews und bessere Qualität.

## Beispiel

Beispiel für einen Feature Branch:

`feat/login-system`

Dieser Branch wird für die Entwicklung eines Login-Systems erstellt. Nach Abschluss der Entwicklung wird der Branch über einen Pull Request in den `main` Branch integriert.