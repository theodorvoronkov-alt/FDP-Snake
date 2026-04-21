# 🐍 FDP Leipzig Snake

Ein Snake-Spiel im FDP-Design, bei dem Alex der Schlangenkopf ist und seine politischen Gegner verspeist.

## Spielprinzip

- **Schlangenkopf**: Alex (mit echtem Foto)
- **Gegner**: Die anderen Personen tauchen als Futter auf
- Die Schlange wächst mit jedem "gefressenen" Gegner
- Das Spiel wird mit der Zeit schneller

## Steuerung

| Taste | Aktion |
|-------|--------|
| `↑` / `W` | Nach oben |
| `↓` / `S` | Nach unten |
| `←` / `A` | Nach links |
| `→` / `D` | Nach rechts |

## Starten

Einfach `index.html` im Browser öffnen – keine Installation nötig!

```
open index.html
```

Oder einen lokalen Server starten:

```bash
npx serve .
# oder
python3 -m http.server 8080
```

## Technik

- Reines HTML5 / Canvas / JavaScript
- Keine externen Abhängigkeiten
- Alle Bilder eingebettet (Base64)
- GitHub-ready: nur `index.html` + `README.md`

## Punkte

- +10 Punkte pro gefressen Gegner (+ Bonus je nach Schlangenlänge)
- Alle 50 Punkte steigt das Level und die Geschwindigkeit erhöht sich
