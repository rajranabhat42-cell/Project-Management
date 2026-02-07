# Project-Management
# Assignment One: Project Management Plan

## Project: Campus-Connect  
**Project Manager:** Raj Bahadur Bhat  
**Team:** Inshal Zahid, Muhammad Hassnain, Fabio Bustamante Romilo, Rajja  
**Project Duration:** 6 Months (Jan 28 – Jul 28)

---

## Project Overview
Campus-Connect is a web-based platform that is made to help college students discover ongoing and upcoming campus events, access all the academic resources, and communicate with different student clubs in one common application. This platform helps students stay engaged by providing relevant events recommendations, all the campus announcements and updates, and available resources.

---

## 1. Skills Assessment
According to our team meeting, the team members have following skills:

| Name | Roles | Skills |
|----|----|----|
| Inshal Zahid | Frontend Developer | HTML, CSS, JavaScript, React |
| Muhammad Hassnain | Backend Developer | Python, Django, Database |
| Rajaa | Full-stack Developer | JavaScript, Node.js, MongoDB |
| Fabio Bustamante Romilo | UI/UX Designer | Figma, Adobe XD, UI design |
| Raj (Me) | Project Manager | Planning, Coordination, Testing |

**Team Skills:**  
This team is made up of a good mix of front-end developer, back-end developer, and an experienced designer, which is essential to create a successful web application.

---

## 2. Project Timeline
The project duration is 6 months which is divided into three payment-based milestones:

- **Month 1 – Requirements Review**
- **Months 2 to 5 – Implementation and Design Review**
- **Month 6 – Final Delivery**

Each phase must be reviewed and approved before the project proceeds to the next stage.

---

## 4. Requirements Review Phase
**Purpose:**  
The goal of this phase is to verify that all functional and non-functional requirements are clearly defined and sufficient to design the Campus-Connect platform.

**Inputs:**  
- Requirements document provided by the development team

**Key Activities:**
- Review core features such as event listings, user accounts, notifications, and resource directories
- Examine non-functional requirements including performance, accessibility, and security
- Validate user roles including students, event organizers, and administrators
- Identify unclear or missing requirements
- Document approval before proceeding to development

---

## 5. Project Planning and Task Management
Project activities are managed using **GitHub Projects** to simulate an industry-style project workflow. The board follows a structured lifecycle:

**Backlog → To Do → In Progress → Review → Done**

Tasks are assigned based on team expertise and include descriptions, deadlines, and status tracking to ensure visibility and accountability.

---

## 6. Implementation and Design Review Phase
**Purpose:**  
To ensure that the system design and initial software implementation align with approved requirements.

**Inputs:**  
- Design documentation  
- Initial prototype

**Key Activities:**
- Review architectural decisions and technology choices
- Test integration between frontend and backend components
- Perform usability testing with sample users
- Identify technical or design improvements

---

## 7. Final Delivery Phase
**Purpose:**  
The final phase focuses on delivering a stable and complete version of Campus-Connect to stakeholders.

**Inputs:**  
- Final software release  
- Technical and user documentation

**Key Activities:**
- Final testing and bug fixes
- Deployment to hosting environment
- Completion of user documentation
- Formal project acceptance

---

## 8. Reflection
This project provides a realistic simulation of managing a software development effort within defined timelines and milestone-based approvals. The scope is appropriate for an academic environment and closely connected to student needs. Overall, this assignment strengthens planning, communication, and coordination skills required in real-world software projects.

---

## 9. Project Timeline (Mermaid)
```mermaid
gantt
    title Campus-Connect Project Timeline (6 Months)
    dateFormat  YYYY-MM-DD
    axisFormat  %b %Y

    section Payment Milestone 1: Requirements Review
    Project Kickoff & Planning        :2025-01-28, 7d
    Requirements Review & Validation  :2025-02-01, 21d
    Requirements Approval             :milestone, 2025-02-28, 0d

    section Payment Milestone 2: Implementation & Design Review
    UI/UX Design & Wireframes          :2025-03-01, 30d
    Frontend & Backend Development    :2025-03-15, 60d
    Integration & Usability Testing   :2025-05-01, 30d
    Design & Implementation Review   :milestone, 2025-05-31, 0d

    section Payment Milestone 3: Final Delivery
    Final Testing & Bug Fixes         :2025-06-01, 30d
    Deployment & Documentation       :2025-07-01, 21d
    Final Delivery & Acceptance      :milestone, 2025-07-28, 0d
