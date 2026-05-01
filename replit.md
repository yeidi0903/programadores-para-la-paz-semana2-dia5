# Programadores para la Paz – Semana 2 Día 5

## Project Overview

A static educational web project for teaching students how to build accessible web forms. The project focuses on HTML/CSS form construction with accessibility principles, clear language, and responsible data minimization.

## Structure

- `semana2/` — Active development directory
  - `index.html` — The web form (Participa)
  - `styles.css` — Form styling
  - `checklist-accesibilidad.txt` — Accessibility checklist for students
  - `reflexion-verificacion.txt` — Reflection document on information verification
- `instrucciones/` — Pedagogical guidance for the activity
- `README.md` — Main instructions and Git-based submission workflow

## Running the App

The project is served as a static site using Python's built-in HTTP server:

```
python3 -m http.server 5000 --directory semana2
```

Available at port 5000 (webview).

## Deployment

Configured as a **static** deployment targeting the `semana2/` directory.

## Tech Stack

- HTML5
- CSS3
- No build system or package manager required
