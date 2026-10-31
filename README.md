# PaperPilot — Capstone 64

A responsive, browser-based project for **Research Paper Reading and Summarisation Assistant**.

## Run the project
1. Extract `Research_Paper_Assistant.zip`.
2. Open the `research_assistant_project` folder.
3. Double-click `index.html` (Chrome is recommended).
4. Start in **Paper analyzer** and use **Load sample paper** to test the workflow.

No installation, server, database or API key is required for this demo. Data is saved in the browser's local storage on the device where it is used.

## Features
- Responsive dashboard and capstone workflow
- Paper analyzer with structured, extractive summary sections
- Paper library with source links
- Ten-point paper-summary verification checklist
- Six-paper comparison matrix with CSV export
- 1,500-word synthesis structure and draft export
- Six-slide presentation outline
- Ten-question research-reading quiz
- Reusable prompt library and workspace JSON export

## Important project limitation
The built-in analyzer is a local extractive text-processing demonstration. It does not call ChatGPT, Gemini, Claude, Elicit or another hosted AI model. It selects sentences from text pasted by the user based on topic keywords. For genuine generative AI integration, a backend service and an API key are required. Never put a private API key in browser JavaScript or publish it in a public GitHub repository.

## Suggested research workflow
1. Select one focused research topic.
2. Find six relevant open-access papers using trusted sources such as arXiv, PubMed Central and journal websites. Verify that each source is legitimate and accessible.
3. Enter paper details and paste relevant text from each paper into the analyzer.
4. Save each paper to the library.
5. Compare each generated draft with the abstract, methodology and results in the original paper. Complete the verification checklist.
6. Fill the comparison matrix using verified details only.
7. Write a thematic synthesis using the provided structure. Add only citations you have personally verified.
8. Prepare the six-slide presentation and quiz demonstration.
9. Disclose AI use according to your institution's rules.

## GitHub Pages deployment
1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, `app.js` and `README.md` to the repository root (not inside an extra nested folder).
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
5. Wait for GitHub Pages to publish the site and open the URL shown on the Pages settings screen.

## Deliverables represented
Research report workspace, verification checklist, paper list, summary checks, comparison matrix, synthesis draft, presentation outline, simple text-to-summary automation, prompt library, verification report support and demo quiz.

## Academic integrity
This project does not guarantee that a paper is reliable or that a summary is correct. Check all claims against the original source. Do not invent references, results or author details. Use open-access material and disclose AI assistance.
