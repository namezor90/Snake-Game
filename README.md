# 🐍 Snake Game

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Klasszikus Snake játék Python Turtle grafikával megvalósítva. Irányítsd a kígyót, gyűjtsd az ételeket és növeld a pontszámodat!

## ✨ Jellemzők

- 🎮 Klasszikus Snake játékmenet
- 📊 Pontszámkövetés
- 🎨 Színes grafikus felület
- ⌨️ Billentyűzetes irányítás
- 🔄 Folyamatos játékmenet
- 💥 Ütközésérzékelés

## 🚀 Telepítés

```bash
git clone https://github.com/namezor90/snake-game.git
cd snake-game
python main.py
```

## 💻 Használat

1. Indítsd el a játékot
2. Irányítsd a kígyót a nyilakkal:
   - ⬆️ Fel
   - ⬇️ Le
   - ⬅️ Balra
   - ➡️ Jobbra
3. Gyűjtsd össze a kék ételeket
4. Kerüld a falakat és a kígyó testét
5. Kattints a képernyőre a játék végén a kilépéshez

## 📁 Projekt Struktúra

```
snake-game/
├── main.py       # Fő játék logika
├── snake.py      # Kígyó osztály
├── food.py       # Étel osztály
└── scoreboard.py # Pontszám kezelés
```

## 🎯 Játékszabályok

- A kígyó folyamatosan mozog
- Az étel megevése növeli a pontszámot és a kígyó hosszát
- A játék véget ér ha:
  - A kígyó falnak ütközik
  - A kígyó saját magának ütközik

## 🛠️ Fejlesztés

A játék könnyen testreszabható a konstansok módosításával:
```python
MOVE_DISTANCE = 20  # Mozgási sebesség
STARTING_POSITION = [(0, 0), (-20, 0), (-40, 0)]  # Kezdő pozíció
ALIGNMENT = 'center'  # Szöveg igazítás
FONT = ('Courier', 20, 'normal')  # Betűtípus beállítások
```

## 📝 Licensz

[MIT](LICENSE)

## 🤝 Közreműködés

1. Fork-old a projektet
2. Hozz létre egy új branch-et (`git checkout -b feature/awesome`)
3. Commit-old a változtatásokat (`git commit -m 'Add awesome feature'`)
4. Push-old a branch-et (`git push origin feature/awesome`)
5. Nyiss egy Pull Request-et

## 👥 Szerzők

- [@namezor90](https://github.com/namezor90)

## 🎮 Jövőbeli fejlesztési lehetőségek

- 🏆 Magas pontszám mentése
- 🎵 Hangeffektek
- 🏁 Különböző nehézségi szintek
- 🌈 Különböző pályák
- 💫 Speciális ételek és képességek
- 🎨 Testreszabható kígyó kinézet
