---
applyTo: "docs/prd/**"
---

Use this folder only to store the PRD (product reqiurment document) and related support files.
when generateing a specific artifect, you must follow this standard.

The general filename rule is:
  - 'prd-[feature].md' for the PRD file
  - For supporting files, no specific rule

For PRD (product reqiurment document), it must contain the following items (it the given sequence):

[Title: PRD - Product / Feature Name]

- Document Informations
    + Product / Feature name
    + Author: The assignee's usernmame
    + Date: blank
    + Version: blank
 
- Table of Contents\
  Includes items up to the second-level header

- Overview
  + Background: Why are we building this?
  + Objective: what problem are we solving?
  + Goals: What do we want to achive?
 
- Provlem Statement
  + Describe the user pain point or business problem.
  + Who is affected (the key users)?
  + Why is this importent now?
 
- Functional Requirments
  +  Ensure the functional requirements are designed to solve the problem statment.
  +  Write all the functional user stories here. For each user story, it must contain:
    - title
    - statement: **As a** <type of user>, **I want** <goal>, **so that** <reason/benifit>.
    - requirement details explaining the statment
    - acceptance criteria, in **given-when-then** format
- Non-Functional Requirements\
  Leave it blank
- Dependancy & Constraints\
  State explicitly any limitations (e.g., only for desktop web, not mobile yet).

- Success Metrics
  + How do we measure success?
  + Example
      - Increase signup conversion rate by 15%
      - Reduce drop-off rate by 10%
      - Improve task completion time by 20%
