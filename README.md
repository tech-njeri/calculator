# Calculator
 
A simple, functional calculator built with vanilla HTML, CSS, and JavaScript — no frameworks, no libraries. Built as a learning exercise and portfolio piece to practice DOM manipulation, expression evaluation, and neumorphic UI design.
 
## Features
 
- Standard arithmetic: addition, subtraction, multiplication, division
- Percentage calculations
- Live expression + result display (shows what you typed *and* the running result, like a phone calculator)
- Clear (`AC`) and single-character delete (`C`)
- Neumorphic (soft UI) button styling
## Built with
 
- HTML5
- CSS3 (Flexbox, CSS Grid, neumorphic shadow styling)
- Vanilla JavaScript (no libraries or frameworks)
## What I learned
 
- Managing UI state without a framework (tracking the current expression as a string vs. tracking `firstValue` / `operator` separately)
- CSS Grid for button layouts vs. Flexbox for centering
- Debugging the classic `box-sizing` width mismatch issue
- Building a neumorphic design system (matching background and shadow tones)
- Deploying a static site with GitHub Pages
## Running locally
 
Clone the repo and open `index.html` directly in your browser — no build step or dependencies required.
 
```bash
git clone https://github.com/yourusername/calculator.git
cd calculator
open index.html
```
 
## Possible next steps
 
- Keyboard input support
- Calculation history
- Light/dark theme toggle
