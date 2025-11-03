# CodeFlowAI

An automated documentation management system that helps maintain up-to-date documentation through automated pull requests.

## Features

- Automatically detects missing or outdated documentation
- Creates pull requests for documentation updates
- Uses customizable system prompts for consistent documentation style
- Manages GitHub integration through environment variables

## Project Structure

- `/src/config/` - Environment and configuration files
- `/src/system_prompts/` - Documentation templates and system prompts
- Root level - Project configuration files (poetry.lock, pyproject.toml, .gitignore)

## Setup

1. Configure environment variables in `src/config/env_vars.py`
2. Install dependencies using Poetry
3. Run the documentation update workflow

## Development

This project is under active development. More features coming soon!