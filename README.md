# StitchBoard

CodePath WEB103 Final Project

Designed and developed by: Zamijah Shakeur-Tompkins, [Teammate 1], [Teammate 2], [Teammate 3]

🔗 Link to deployed app: _Coming soon (will be deployed on Render)_

## About

### Description and Purpose

StitchBoard is a web app for crocheters who want to make more of their craft than a finished project sitting on a shelf. Users can browse a library of patterns, see exactly which yarn and hooks each one needs, and start their own projects from those patterns. They can track each project from "Not Started" to "Finished" and keep notes on changes they made along the way.

The purpose is to give crocheters one organized place for their work, so planning, materials, and progress live together instead of in scattered notes, screenshots, and bookmarks. By keeping a clear record of what they've made and how, crocheters can more easily share their process and build a body of work they can show others.

### Inspiration

I love to crochet, and I've spent a lot of time thinking about what to do with that skill. Instead of trying to sell every project I make, I want to focus on creating content around my crochet: sharing the process, the patterns, and the finished pieces. To do that well, I need a way to stay organized, knowing what I'm working on, what materials I need, and what I've finished. StitchBoard started as the tool I wish I had, and I think other crocheters who want to share their craft will find it useful too.

## Tech Stack

Frontend: React, React Router

Backend: Node.js, Express, PostgreSQL

Deployment: Render

## Features

### Pattern Library

Browse all crochet patterns with their difficulty level and category.

[gif goes here]

### Pattern Detail Page

View a pattern's full description and materials list on its own page, using a dynamic route.

[gif goes here]

### Project Tracker

Create, view, edit, and delete your own crochet projects through a RESTful API (GET, POST, PATCH, DELETE).

[gif goes here]

### Materials List

See the yarn and hooks each pattern needs, including the quantity of each. This uses a many-to-many relationship with a join table that stores a unique quantity field.

[gif goes here]

### Filter and Sort

Narrow patterns by difficulty, category, or yarn weight, and sort the results.

[gif goes here]

### Progress Status

Mark projects as Not Started, In Progress, or Finished without leaving the page.

[gif goes here]

### Reset Database

Restore the default patterns, materials, and sample projects with one action.

[gif goes here]

## Installation Instructions

_To be updated as development progresses._

1. Clone the repository and open the project folder.
2. Install dependencies for both apps:
```
   cd server && npm install
   cd ../client && npm install
```
3. Create a PostgreSQL database and add a `.env` file in `server/` with your connection string (for example, `DATABASE_URL=...`).
4. Set up and seed the database (script name to be added once created).
5. Start the backend from `server/` and the frontend from `client/`.
