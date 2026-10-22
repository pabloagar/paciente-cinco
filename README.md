# Paciente Cinco

**English** · [Leer en español](README.es.md)

**Five-minute clinical cases. One decision at a time.**

An educational prototype for medical students, interns and physicians who want to practice with short cases, make decisions and reflect on their reasoning through feedback.

[Play the demo](https://paciente-cinco-demo.pablo-aguirre.chatgpt.site)

**Educational beta:** demonstration content awaits clinical review. The demo is intended to explore the learning experience; it does not certify competence and is not intended to guide patient care.

<picture>
  <source media="(max-width: 600px)" srcset="assets/screenshots/turno-mobile.webp">
  <img src="assets/screenshots/turno-desktop.webp" alt="Paciente Cinco beta 0.5.1: first guided consultation, educational warning and learning map; no real patient data" width="100%">
</picture>

Public demo, October 22, 2026. Spanish interface; the beta warning remains visible. [Mobile capture (390 × 844, 2×)](assets/screenshots/turno-mobile.webp) · [Capture provenance](assets/screenshots/README.md).

## The idea

Explore short practice sessions built around a case, a decision and an opportunity to revisit what was learned. The experience combines guided consultations, practice activities and review, with progress saved on the device.

## What you can try

- A guided introduction to a primary care setting.
- Activities involving clinical decisions, ECGs and respiratory sounds.
- Feedback and references to revisit answers.
- A learning map, practice and review.
- Resuming activities and checking locally stored progress.

## What this presentation demonstrates

The demo and screenshots let visitors inspect the interface and introductory journey. They do not establish clinical accuracy, learning effectiveness or professional competence. The implementation summary is maintainer-documented; the internal code cannot be audited from this public repository.

## Project status

The public demo is on the 0.5 beta line; the mobile capture shows version 0.5.1. Clinical content review and physical phone testing are still pending. Its effect on learning has not yet been evaluated.

The development code remains private. This overview makes the project accessible without access to the internal repository.

## My contribution

**Dr. Pablo Aguirre Araya, physician in Chile's MGZ public service program, Arica.** Educational concept, learning journeys and product decisions, with iterative AI-assisted development. Formal clinical review of the content remains a separate, pending step.

## Design and technology

A web app built with TypeScript, React and Vite. Progress is stored in the browser using IndexedDB. Its editorial workflow separates drafts, review and content eligible for distribution.

There is no live generative chat during gameplay. Answers and feedback come from the content prepared for each activity.

## Demo limitations

- Local progress, without accounts or cross-device synchronization.
- Schematic ECG traces, not calibrated for diagnosis.
- Review requests are saved locally and can be exported; they are not automatically sent to a server.
- Some areas of the map represent future development.

## What I want to learn from testing

Whether the first session is understandable, whether decisions and feedback are clear, and whether an activity is easy to resume. Initial observations will help improve the experience before evaluating educational outcomes.

[Try the demo](https://paciente-cinco-demo.pablo-aguirre.chatgpt.site) · [Send feedback by email](mailto:pablo.aguirre.araya@gmail.com)
