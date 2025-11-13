---
name: "Feature: Persistent Database"
about: "Add persistent database support to store activities and participants."
title: "[Feature] Persistent Database Support"
labels: [enhancement]
assignees: []
---

**Problem:**
Currently, all data is stored in memory and lost on server restart.

**Proposed Solution:**
Integrate a persistent database (e.g., SQLite or PostgreSQL) to store activities, participants, and signups.

**Benefits:**
- Data is not lost on restart
- Enables future features like reporting, analytics, and user management

**Additional context:**
See Evolvve-Student-Chapter-App for reference.