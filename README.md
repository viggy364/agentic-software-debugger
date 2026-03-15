# Agentic Software Debugger & Documenter

A multi-agent AI system that automatically detects bugs, fixes code, and generates documentation using LLM-based workflows.

## Project Overview

This project uses agentic AI patterns to build a developer tool that transforms buggy and undocumented code into clean and documented output.

### Workflow

1. **Linter Agent** analyzes the code and detects errors.
2. **Fixer Agent** attempts to automatically repair the code.
3. **Loop Controller** re-runs the process until errors are fixed or max iterations reached.
4. **Documentation Agent** generates Markdown documentation for the final code.

## Tech Stack

- Python
- Google ADK
- Gemini Flash Models
- Pylint / Flake8
- Multi-Agent Architecture

## Project Structure
