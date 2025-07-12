# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a static HTML project for golf trip planning. The repository contains a comprehensive golf trip comparison website that analyzes multiple destinations for group golf trips.

## Project Structure

- `README.md` - Basic project description
- `golf_trip_spreadsheet.html` - Main application file containing the complete golf trip planning interface

## Technology Stack

This is a pure HTML/CSS/JavaScript project with no build process or dependencies:

- **Frontend**: Vanilla HTML5, CSS3, JavaScript
- **Styling**: Inline CSS with gradient backgrounds and responsive grid layouts
- **Interactivity**: Pure JavaScript for tab navigation and data export functionality
- **No framework dependencies**: Self-contained single-page application

## Development Workflow

Since this is a static HTML project, there are no build commands, test suites, or development servers to run. Development is straightforward:

1. **Editing**: Open `golf_trip_spreadsheet.html` in any text editor
2. **Testing**: Open the file directly in a web browser
3. **Deployment**: The HTML file can be served from any web server or opened locally

## Application Features

The golf trip planning application includes:

- **Tabbed interface** with 8 different sections (Overview, Expert Picks, and 6 destination tabs)
- **Comprehensive golf course data** with rates, rankings, and features
- **Export functionality** including CSV export, print/PDF, and clipboard copy
- **Interactive itinerary generator** for selected destinations
- **Responsive design** with CSS Grid layouts

## Data Structure

All golf course and destination data is embedded directly in the HTML file as:
- Structured HTML tables with course information
- JavaScript arrays/objects for export functionality
- Inline styling for visual presentation

## Common Tasks

- **Add new golf course**: Edit the appropriate destination tab's table in the HTML
- **Update pricing**: Modify the table cells with class "price"
- **Add new destination**: Create new tab button and corresponding div with class "tab-content"
- **Modify export data**: Update the JavaScript functions at the bottom of the file

## File Organization

The single HTML file is organized with:
- CSS styles in the `<head>` section
- Main content in tabbed div structure
- JavaScript functions at the bottom for interactivity

No external dependencies or build tools are required for this project.