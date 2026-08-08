# OctoAcme Project Management Processes

## Overview
OctoAcme uses a structured, iterative approach to project management that emphasizes customer value, clear ownership, data-informed decisions, and continuous improvement. Projects begin with a lightweight initiation step to confirm the problem, stakeholders, and success metrics. Approved initiatives are broken into prioritized, shippable increments and planned with clear acceptance criteria and a Definition of Done so teams can deliver predictable, testable outcomes.

Day-to-day delivery follows a clear workflow and team rhythm to enable fast feedback and safe deployments. Work moves through a project board (Backlog → Ready → In Progress → In Review → QA → Done), pull requests are intentionally small and CI-first, and regular ceremonies (daily standups, weekly delivery syncs, and end-of-sprint demos) keep teams aligned. Risk and dependencies are tracked in a simple Risk Register with defined escalation paths from team-level triage to sponsor-level escalation when needed.

Roles and responsibilities are explicit so ownership is clear: Product Managers (PdM) define objectives and success metrics, Project Managers (PM) coordinate delivery and communications, Developers implement and test features, and QA validates acceptance criteria. Key artifacts — the Project One-pager, backlog with acceptance criteria, risk register, release notes, and retrospective action items — live in the repository as a single source of truth for teams and stakeholders.

Quality assurance is built into each step: unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI pipelines, and manual QA when appropriate before releases. Releases require passing CI/security checks, documented rollback plans, and staged verification (staging smoke tests and post-deploy checks) to minimize risk. Retrospectives after sprints, releases, or incidents convert learnings into tracked action items that feed back into the backlog for measurable continuous improvement.

## Process documents
- Project Management Overview: ./octoacme-project-management-overview.md
- Project Initiation Guide: ./octoacme-project-initiation.md
- Project Planning: ./octoacme-project-planning.md
- Execution & Tracking: ./octoacme-execution-and-tracking.md
- Release & Deployment Guide: ./octoacme-release-and-deployment.md
- Risk Management & Communication: ./octoacme-risks-and-communication.md
- Retrospective & Continuous Improvement: ./octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas: ./octoacme-roles-and-personas.md

## How to use this README
Start with the Project Management Overview to understand roles and cadence. For a new initiative, use the Project Initiation Guide and the Project One-pager template to capture the problem and success metrics. During planning, consult Project Planning for backlog and DoD guidance. During delivery, follow Execution & Tracking along with the Release & Deployment guide for safe rollouts. Use the Risk & Communication doc to manage and escalate risks, and capture improvements in Retrospective & Continuous Improvement.

## Getting started (for new team members)
1. Read the Project Management Overview.
2. Browse the linked process documents above for the phase you’re entering (initiation → planning → execution → release → retrospective).
3. Look for the Project One-pager and the project board in the repo to see active work and owners.
4. If you need to update or propose additions to any process doc, use the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` issue template and reference the document you want to change.
