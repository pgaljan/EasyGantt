# EasyGantt
EasyGantt is an excel template that generates GANTT-flavored plantuml markup.

## Features
- 3-level timebox (phase/sprint/event)
- Time-based progress indication
- Configurable frontmatter/style
- Linked task visual indicators
- Configurable Start/End

# Input
<img src="https://github.com/user-attachments/assets/0dd8c61c-d683-4c08-82ea-5dcf73f11589" alt="EasyGantt Input" width="500" height="600">

# Rendered GANTT

![image](https://github.com/user-attachments/assets/cc5222b3-8bb3-445e-9770-18f4fc46647b)

# Puml markup
```startuml
@startgantt
<style>
ganttDiagram {
task {
BackGroundColor #ffe6e6
LineColor White
}
undone {
BackGroundColor LightGray
}
}
</style>
title Atlas Sprint Schedule
projectscale monthly zoom 3
hide footbox
footer generated: %date("YYYY-MM-dd")
Project starts 2024-11-18
[Ideate] starts on 2024-11-19 and ends on 2024-12-19
[Proof of Concept] starts on 2024-12-20 and ends on 2025-03-19
[Architect] starts on 2024-12-20 and ends on 2025-01-03
[Design] starts on 2025-01-04 and ends on 2025-01-18
[Backend] starts on 2025-01-19 and ends on 2025-02-02
[Frontend] starts on 2025-02-03 and ends on 2025-02-17
[Integrate] starts on 2025-02-18 and ends on 2025-03-04
[Onboarding] starts on 2025-03-05 and ends on 2025-03-19
[Prototype] starts on 2025-03-20 and ends on 2025-08-05
[Admin & Invites] starts on 2025-03-20 and ends on 2025-04-09
[Renderer R&D] starts on 2025-04-09 and ends on 2025-04-22
[Quill Enhancements - pictures, tables] starts on 2025-04-23 and ends on 2025-05-07
[Markdown] starts on 2025-05-08 and ends on 2025-05-22
[PlantUML & Latex] starts on 2025-05-23 and ends on 2025-06-06
[Content Safety API] starts on 2025-06-07 and ends on 2025-06-21
[Structure Sharing] starts on 2025-06-22 and ends on 2025-07-06
[Cross-Structure Reporting] starts on 2025-07-07 and ends on 2025-07-21
[User Metrics] starts on 2025-07-22 and ends on 2025-08-05
[Restricted Preview] starts on 2025-08-06 and ends on 2025-12-03
[Platform Metrics & Alerting] starts on 2025-08-06 and ends on 2025-08-20
[Test Automation ] starts on 2025-08-21 and ends on 2025-09-04
[Web Analytics] starts on 2025-09-05 and ends on 2025-09-19
[LLM Ingest] starts on 2025-09-20 and ends on 2025-10-04
[Penetration Testing] starts on 2025-10-05 and ends on 2025-10-19
[Cost Optimization] starts on 2025-10-20 and ends on 2025-11-03
[Automated Scaling] starts on 2025-11-04 and ends on 2025-11-18
[Payment Processing] starts on 2025-11-19 and ends on 2025-12-03
[Invite Preview] starts on 2025-12-04 and ends on 2026-02-16
[Design Review] starts on 2025-12-04 and ends on 2025-12-18
[Design Adaptation] starts on 2025-12-19 and ends on 2026-01-02
[Regulatory Review] starts on 2026-01-03 and ends on 2026-01-17
[User Acq. & Marketing plan] starts on 2026-01-18 and ends on 2026-02-01
[Business Plan] starts on 2026-02-02 and ends on 2026-02-16
[Launch] happens on 2026-02-17
[Ideate] is 100% completed
[Proof of Concept] is 100% completed
[Architect] is 100% completed
[Design] is 100% completed
[Backend] is 100% completed
[Frontend] is 100% completed
[Integrate] is 100% completed
[Onboarding] is 100% completed
[Prototype] is 15.9420289855072% completed
[Admin & Invites] is 100% completed
[Renderer R&D] is 15.3846153846154% completed
[Quill Enhancements - pictures, tables] is 0% completed
[Markdown] is 0% completed
[PlantUML & Latex] is 0% completed
[Content Safety API] is 0% completed
[Structure Sharing] is 0% completed
[Cross-Structure Reporting] is 0% completed
[User Metrics] is 0% completed
[Restricted Preview] is 0% completed
[Platform Metrics & Alerting] is 0% completed
[Test Automation ] is 0% completed
[Web Analytics] is 0% completed
[LLM Ingest] is 0% completed
[Penetration Testing] is 0% completed
[Cost Optimization] is 0% completed
[Automated Scaling] is 0% completed
[Payment Processing] is 0% completed
[Invite Preview] is 0% completed
[Design Review] is 0% completed
[Design Adaptation] is 0% completed
[Regulatory Review] is 0% completed
[User Acq. & Marketing plan] is 0% completed
[Business Plan] is 0% completed
@endgantt
```
