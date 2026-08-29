# calculator
A simple, responsive calculator built with HTML, CSS Grid, and vanilla JavaScript — supports basic arithmetic, keyboard input, and a clean dark UI.
# Calculator

A simple, responsive calculator built with **HTML, CSS Grid, and vanilla JavaScript**. No frameworks, no dependencies — just one self-contained file.

🔗 **Live demo:** _add your GitHub Pages link here_

## Features

- Basic operations: addition, subtraction, multiplication, division
- Percentage (%) and delete (DEL) support
- Keyboard input supported (numbers, `+ - * /`, `Enter`, `Backspace`, `Esc`)
- Responsive layout — works on desktop and mobile
- Clean dark UI with hover and press animations

## Built With

- **HTML5** — structure
- **CSS Grid** — button layout
- **JavaScript (vanilla)** — calculator logic, event listeners

## Getting Started

Just open `index.html` in any browser — no installation or build step required.

```bash
git clone https://github.com/your-username/calculator-app.git
cd calculator-app
open index.html
```

## How It Works

- Each button has a `data-number` or `data-action` attribute.
- A single event listener loop attaches click handlers to every button.
- Calculations are handled with if-else logic based on the selected operator.
- The display updates in real time as you type.

## License

Free to use for learning and personal projects.
