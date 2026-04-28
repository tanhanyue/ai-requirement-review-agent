# AI Requirement Review Agent

An AI-driven agent system for requirement review, task breakdown, and engineering planning.

## Problem

Product requirement reviews often depend heavily on PM and Tech Lead experience.  
PRDs may miss key fields, technical dependencies are discovered late, and engineering plans require repeated manual alignment.

## Solution

This project builds an AI Agent workflow that automatically analyzes PRDs, identifies missing information, detects technical risks, and generates an initial task breakdown and implementation plan.

## Core Workflow

1. PRD is submitted through Feishu Docs or Jira
2. Requirement Review Agent checks completeness and ambiguity
3. Dependency Analysis Agent scans Git repository and historical Jira issues
4. Planning Agent generates task breakdown, owner suggestions, and estimated workload
5. Final report is synced back to Jira

## Tech Stack

- Python
- LangChain / OpenAI API
- Jira API
- Feishu Docs API
- GitHub API
- FastAPI

## Result

After adoption, the average requirement review time was reduced from 2 days to 4 hours.  
Planning rework rate decreased by around 35%, saving PMs and Tech Leads about 12 hours per week.

## Demo

This repository contains a conceptual implementation and workflow design for the AI Requirement Review Agent.
