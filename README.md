# Large_scale_software_design_project
# Academic Code Review Platform

Full-stack **Django REST + React** platform for classroom code review. Students submit code, highlight lines, and leave inline comments; instructors create/close assignments, manage roles, and track progress. Built with **JWT auth**, **PostgreSQL**, unit tests, CI, and accessible UI patterns.

## Features
- Role-based access: student / instructor / admin
- Submissions: upload code, syntax highlight, version history
- Inline annotations: line-level comments, threads, resolve state
- Assignments: create, publish, close; due dates & status
- Progress dashboards: per-student and per-assignment
- REST API (DRF): pagination, filters, consistent JSON errors
- Auth: JWT (access/refresh), password reset
- Solid UX: loading/empty states, keyboard shortcuts

## Tech Stack
**Backend:** Python, Django, Django REST Framework, PostgreSQL, djangorestframework-simplejwt  
**Frontend:** React, Vite  
**Tooling:** Pytest, React Testing Library, GitHub/GitLab CI, Docker (optional)



