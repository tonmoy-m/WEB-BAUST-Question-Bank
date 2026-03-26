# 📚 BAUST Question Bank (MVP)

A frontend utility application designed to solve a specific problem for the student body: navigating and accessing fragmented academic resources and past exam questions. 

This repository houses the **Minimum Viable Product (MVP)** developed to rapidly prototype the user interface and resource routing logic. 

## 🎓 Academic Background

This project was developed collaboratively as part of a foundational software engineering course. The primary focus was on the Software Development Life Cycle (SDLC), team coordination, and product design, rather than complex backend architecture.

* **Course:** CSE 2100 - Software Development Project I
* **Type:** Group Project
* **Core Focus:** Product ideation, requirement gathering, and rapid UI prototyping.

## 🎯 The Problem & Solution

* **The Problem:** Students previously had to manually search through disorganized folders or rely on seniors to find past CT, Midterm, and Final questions.
* **The Solution:** A centralized, accessible web portal that dynamically filters study materials by Department, Level, Term, and Examination Type, routing users directly to the correct Google Drive repository.

## 💡 Reflections & Potential Optimizations

Since developing this initial MVP, my understanding of software architecture has grown significantly. While the current build successfully solves the core user problem, there are several ways this codebase could be modernized or scaled if it were to be expanded:

* **Separation of Concerns:** A logical optimization would be extracting the embedded JavaScript logic into modular `app.js` files to improve maintainability.
* **Data Abstraction:** The hardcoded `if/else` routing block could be refactored into a scalable JSON data structure or connected to a lightweight database.
* **Framework Integration:** If the application's feature set were to grow, migrating the vanilla UI to a component-based framework (like React or Vue) would offer much better state management.

## 🛠️ Current Tech Stack
* HTML5, CSS3, Vanilla JavaScript (Embedded)

## 💻 How to Run
1. Clone this repository.
2. Open the directory and launch `index.html` in any modern web browser.
