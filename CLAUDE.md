# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple timeline visualization project for GutCam using Mermaid gantt charts. The project tracks product development milestones and marketing activities from October 2025 through April 2026.

## File Structure

- `README.md` - Contains link to view the timeline
- `timeline.mmd` - Mermaid gantt chart defining the GutCam development timeline

## Timeline Structure

The timeline is organized into two main sections:
- **Product**: Development phases from basic connection through MVP and Version2
- **Marketing**: Landing page and related activities

Key milestones include:
- Start: October 1, 2025
- First hardware/software meet: After 15 days of basic connection dev
- POC ready: After 15 days of POC development
- MVP: January 20, 2026
- Version2: April 20, 2026

## Working with Timeline

When modifying the timeline:
- Use Mermaid gantt syntax
- Maintain consistent date format (YYYY-MM-D)
- Keep milestone dependencies logical (e.g., "dev POC" starts "after meet")
- Consider impact on downstream milestones when adjusting dates