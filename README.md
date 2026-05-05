Website: Student Organizer/planner

User Story: As a student, I want to organize my assignment workflow , to help me turn in assignments on time


Acceptance Criteria
- high priority assignment function
- add/dropping classes folder
- checklist
- Timelines (per assignment)
- notifications for due assignments 
- homework scheduling 
- motivational quote that switches every day
- extra engagement - due this or else - mascot? - garden assignments
- should have an extension for school boards

Student Organizer/Planner - Learning-Focused Project Plan
Project Overview

Build a web-based student assignment organizer tailored for learning. This project teaches full-stack web development fundamentals through a practical, real-world application.
Learning Objectives

    HTML5 semantic structure & forms
    CSS3 layout (Flexbox, Grid) & responsive design
    Vanilla JavaScript (DOM manipulation, events, local storage)
    Basic data persistence (LocalStorage → Firebase)
    Git workflow & version control
    Debugging & browser DevTools
    Accessibility basics (ARIA, semantic HTML)

Phase 1: Foundation - HTML & CSS Basics (Weeks 1-2)

What You'll Learn: Semantic HTML, CSS Grid/Flexbox, Responsive Design

Tasks:

    Create HTML boilerplate with semantic structure
        Header with navigation
        Sidebar for class list
        Main content area for assignments
        Footer

    Style with CSS (no framework initially)
        Mobile-first responsive design
        Flexbox for navigation
        CSS Grid for assignment cards
        Color scheme & typography

    Create static mockup pages
        Dashboard view
        Assignment detail page
        Class management page

Deliverable: Fully styled, responsive HTML/CSS site with no functionality yet
Phase 2: Core Features - JavaScript Fundamentals (Weeks 3-4)

What You'll Learn: DOM manipulation, events, array/object methods, LocalStorage

Tasks:

    Assignment Management (JavaScript)
        Add assignment form with validation
        Store assignments in JavaScript array
        Display assignments as card components
        Edit/delete assignments with event listeners
        Save to browser LocalStorage

    Class Organization
        Add/remove classes with form input
        Filter assignments by selected class
        Display class count on sidebar

    Priority & Sorting
        Add priority dropdown (High/Medium/Low)
        Sort assignments by priority & due date
        Color-code by priority level

Deliverable: Functional assignment organizer with persistent data (LocalStorage)
Phase 3: Enhanced UX - Intermediate JavaScript (Weeks 5-6)

What You'll Learn: Dates/times, arrays/object manipulation, basic animation

Tasks:

    Timelines & Due Dates
        Integrate HTML5 date input
        Calculate days until due
        Display timeline progress bar per assignment
        Highlight overdue assignments in red

    Checklist System
        Add checklist items to assignments
        Check off completed subtasks
        Calculate completion percentage
        Remove completed items

    Daily Motivational Quote
        Create local quote array (20+ quotes)
        Display random quote on page load
        Use localStorage to cache daily quote (change at midnight)
        Add quote refresh button

Deliverable: Assignment tracker with timelines, checklists, and motivational elements
Phase 4: Notifications & Gamification (Weeks 7-8)

What You'll Learn: Browser APIs, CSS animations, state management

Tasks:

    Notifications
        Check due dates daily (on page load)
        Use browser alert() initially, then upgrade to toast notifications
        Create notification component with CSS animations
        Log notifications to a simple notification history

    Gamification - Garden System
        Create simple garden visual (HTML/CSS)
        Each completed assignment = plant a seed/grows flower
        Display garden on dashboard
        Plant characteristics based on assignment priority

    Mascot Character (Optional Challenge)
        Simple SVG mascot or emoji
        Display encouragement messages based on progress
        React to milestones (5 assignments complete, streak of 3 days)

Deliverable: Engaging dashboard with notifications and visual gamification
Phase 5: Data Persistence & Bonus Features (Weeks 9-10)

What You'll Learn: APIs, JSON, async JavaScript, third-party integrations

Tasks:

    Upgrade to Cloud Storage (Optional)
        Migrate LocalStorage to Firebase Realtime Database
        Learn async/await and fetch API
        User authentication basics

    School Board Integration (Extension)
        Research Google Classroom API
        Create mock import feature (read sample JSON data)
        Document API authentication for future use

    Homework Scheduling View
        Create weekly calendar view
        Drag-and-drop assignment scheduling (use HTML5 drag/drop API)
        Export schedule to calendar format (iCal)

Deliverable: Cloud-backed app with optional school board integration
Recommended Tech Stack (Beginner-Friendly)
Layer 	Technology 	Why
HTML 	HTML5 Semantic 	Learn proper structure
CSS 	Vanilla CSS + Flexbox/Grid 	Master layout fundamentals
JavaScript 	Vanilla JS (no frameworks) 	Understand DOM & async patterns
Storage 	LocalStorage → Firebase 	Progress from simple to cloud
Hosting 	GitHub Pages 	Free + learn Git workflows
Tools 	VS Code + DevTools 	Industry-standard debugging
Learning Resources Per Phase
Phase 	Concepts 	Free Resources
1 	HTML5, CSS Grid/Flexbox, Responsive 	MDN Web Docs, CSS-Tricks
2 	JavaScript DOM, Events, Objects, Arrays 	Eloquent JavaScript, FreeCodeCamp
3 	Date APIs, String methods, DOM animations 	JavaScript.info
4 	Browser APIs (localStorage, notifications) 	Web.dev, MDN
5 	Fetch API, JSON, Firebase, Async/Await 	Official Firebase docs
