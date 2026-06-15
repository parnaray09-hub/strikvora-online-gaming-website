# Strikvora

## 1. Overview

### Project Purpose

Strikvora is an online football drafting experience that allows users to assemble a squad from a predefined pool of fictional football players and receive a final squad evaluation based on player statistics, chemistry, synergy, and ranking calculations.

### Product Summary

The website consists of three primary sections:

1. Player Draft Center
2. Squad Builder
3. Draft Results Dashboard

Users browse available players, build a squad, and receive a final performance evaluation based on the rules defined in the provided assets.

### Target Audience

* Football gaming enthusiasts
* Fantasy team building enthusiasts
* Strategy focused users
* Competitive sports simulation users

### Core Functionality

* Display player data from the provided player database
* Allow player selection into a squad
* Display squad composition
* Calculate squad ratings and chemistry values
* Display final rank tiers
* Support desktop and mobile layouts

---

## 2. Scope of Work

### In Scope

#### Player Draft Center

* Display all players contained in `strikvora_player_database.xlsx`
* Display player position
* Display player rating
* Display player club
* Display player attributes
* Support player selection
* Follow the visual direction shown in `strikvora_player_card_reference.png`

#### Squad Builder

* Display selected players
* Allow squad composition management
* Display squad statistics
* Display chemistry values
* Display synergy values
* Apply scoring rules from `strikvora_scoring_rules.pdf`

#### Draft Results Dashboard

* Display final squad rating
* Display chemistry summary
* Display synergy summary
* Display rank tier
* Follow layout guidance from `strikvora_dashboard_reference.png`
* Apply tier definitions from `strikvora_tier_system.pdf`

#### Branding

* Apply colors defined in `strikvora_brand_guidelines.pdf`
* Apply typography defined in `strikvora_brand_guidelines.pdf`
* Use club assets from `strikvora_club_logos.zip`

#### Responsiveness

* Support desktop screens
* Support tablet screens
* Support mobile screens

### Out of Scope

* User accounts
* Authentication systems
* Registration forms
* Login functionality
* Databases
* Server-side processing
* Payment functionality
* Online multiplayer functionality
* Chat systems
* Leaderboards
* External API integrations
* Content management systems
* Cloud deployment configuration

---

## 3. Tech Stack Required

### Frontend Framework

* HTML
* CSS
* JavaScript

### Backend Framework

* Not Required

### Database

* Not Required

### Authentication

* Not Required

### Hosting

* Not Required

### Third Party Integrations

* Not Required

### Development Tools

* Any modern code editor
* Browser developer tools

---

## 4. Folder Structure

```text
project-root/
│
├── assets/
│   ├── strikvora_player_database.xlsx
│   ├── strikvora_club_logos.zip
│   ├── strikvora_scoring_rules.pdf
│   ├── strikvora_brand_guidelines.pdf
│   ├── strikvora_reference_wireframe.png
│   ├── strikvora_tier_system.pdf
│   ├── strikvora_player_card_reference.png
│   └── strikvora_dashboard_reference.png
│
├── css/
│   └── styles.css
│
├── js/
│   └── app.js
│
├── images/
│
├── index.html
│
└── README.md
```

### Directory Explanation

#### assets

Contains all provided project assets.

#### css

Contains responsive styling files.

#### js

Contains interactive functionality and calculations.

#### images

Contains extracted logo assets and supporting imagery.

#### index.html

Main website entry point.

#### README.md

Project setup and structure explanation.

---

## 5. Deliverables

| ID   | Deliverable                  | Type |
| ---- | ---------------------------- | ---- |
| D-01 | Responsive Strikvora Website | HTML |
| D-02 | Player Draft Center          | HTML |
| D-03 | Squad Builder                | HTML |
| D-04 | Draft Results Dashboard      | HTML |
| D-05 | Responsive Layout Support    | CSS  |
| D-06 | Editable Source Files        | ZIP  |

### Deliverable Requirements

#### D-01 Responsive Strikvora Website

Must contain all required sections and function correctly on supported screen sizes.

#### D-02 Player Draft Center

Must display all players from `strikvora_player_database.xlsx`.

#### D-03 Squad Builder

Must allow squad creation and display active squad statistics.

#### D-04 Draft Results Dashboard

Must display final calculated results and rank tier.

#### D-05 Responsive Layout Support

Must adapt layouts for desktop, tablet, and mobile devices.

#### D-06 Editable Source Files

Must include all project source files in editable form.

---

## 6. File Formats

### Source Code

* `.html`
* `.css`
* `.js`

### Assets

* `.xlsx`
* `.zip`
* `.pdf`
* `.png`

### Submission Package

* `.zip`

### Documentation

* `.md`

---

## 7. Explicit Ask

### What Must Be Built

Build a complete Strikvora football drafting website consisting of:

* Player Draft Center
* Squad Builder
* Draft Results Dashboard

The implementation must use:

* `strikvora_player_database.xlsx`
* `strikvora_club_logos.zip`
* `strikvora_scoring_rules.pdf`
* `strikvora_brand_guidelines.pdf`
* `strikvora_reference_wireframe.png`
* `strikvora_tier_system.pdf`
* `strikvora_player_card_reference.png`
* `strikvora_dashboard_reference.png`

### Expected Behavior

#### Player Draft Center

* Display all players
* Display player details
* Support player selection

#### Squad Builder

* Display selected squad
* Display squad statistics
* Display chemistry calculations

#### Draft Results Dashboard

* Display final squad score
* Display synergy summary
* Display rank tier

### Acceptance Criteria

* All players from the database are displayed.
* Club logos are displayed where applicable.
* Scoring logic follows `strikvora_scoring_rules.pdf`.
* Rank assignment follows `strikvora_tier_system.pdf`.
* Branding follows `strikvora_brand_guidelines.pdf`.
* Player cards visually align with `strikvora_player_card_reference.png`.
* Dashboard visually aligns with `strikvora_dashboard_reference.png`.
* Layout adapts correctly across supported screen sizes.
* All deliverables are included.

### Performance Expectations

* Pages load without visual layout breaks.
* Interactive actions respond without noticeable delay.
* Layout remains usable across supported screen sizes.

### Platform Requirements

* Modern desktop browsers
* Modern tablet browsers
* Modern mobile browsers
