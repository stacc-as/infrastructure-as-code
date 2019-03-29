# Presentation (reveal.js)

reveal.js is a framework for easily creating beautiful presentations using HTML. [Check out the live demo](http://revealjs.com/).

## Editing slide

Slides are in the `slides/` folder.

- `\n\n\n` for new slide
- `\n\n` for new sub slide

## Setup

0. Install [Node.js](http://nodejs.org/) (4.0.0 or later)

1. Clone the reveal.js repository
   ```sh
   $ git clone https://github.com/181192/girlpower-intro.git
   ```

2. Navigate to the reveal.js folder
   ```sh
   $ cd presentation
   ```

3. Install dependencies
   ```sh
   $ yarn install
   ```

4. Serve the presentation and monitor source files for changes
   ```sh
   $ yarn dev
   ```

5. Open <http://localhost:8000> to view your presentation

   You can change the port by using `yarn dev -- --port=8001`.