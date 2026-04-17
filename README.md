# QA Engineer | Behavioral Specialist

Software is built by humans, and because human systems are inherently fallible, errors are inevitable. 
I address this by applying a clinical perspective to the **Software Development Lifecycle (SDLC)**.

I transitioned from psychology into Quality Assurance to be a strategic partner within global engineering teams, promoting a culture of quality throughout the development journey. My mission is to **verify and validate** that the products we build don't just "pass tests," but truly solve user needs and provide a seamless, resilient experience for people worldwide.   

I thrive in the structured world of **documentation**, risk-based planning, and test suite execution. I view a product’s codebase as a living system, and my background allows me to diagnose "systemic friction" before it reaches the end user. By merging technical tools like Postman and Playwright with a deep understanding of human-centric reliability, I ensure that software remains as robust as the people who depend on it.

## Why "Behavioral Specialist" in Quality Engineering?

* **Predictive Failure Analysis:** Just as I identified clinical risks in institutional settings, I use **Behavioral Analysis** to predict where a user will encounter friction. This allows me to identify critical "edge cases" that standard automated scripts often miss.
* **Root Cause Integrity:** In healthcare, a documentation error has serious consequences. I treat every bug report with that same level of rigor, performing deep **Root Cause Analysis (RCA)** to ensure the systemic failure is resolved, not just the "symptom" on the UI.
* **Human-Centric Reliability:** I understand that users of medical portals are often in high-stress states. My goal is to ensure software remains **stable and intuitive** exactly when the user needs it most, ensuring data integrity is treated as a matter of safety.

---

## ## 🏛️ Engineering Mindset & Quality Systems
> **“A truly great product is defined by its resilience. I bridge the gap between human error and system integrity through rigorous, risk-based auditing.”**

### **Methodology & Governance**
| Domain | Expertise & Methodology |
| :--- | :--- |
| **Testing Philosophy** | [Rapid Software Testing](https://rapid-software-testing.com/) (RST) mindset focusing on Exploratory Testing and "Breaking the System" via Negative Scenarios. |
| **Security & Resilience** | Utilizing **Security Fuzzing** and input sanitization audits to identify vulnerabilities and prevent unhandled server exceptions. |
| **SDLC Mastery** | Full lifecycle integration: Requirements Analysis → Design/Planning → Execution → Deployment & Monitoring. |
| **Human-System Interaction** | [Behavioral Analysis](https://en.wikipedia.org/wiki/Applied_behavior_analysis) and UX/Usability auditing to ensure products are resilient under human-centric stress. |

### **Testing Ecosystem & Integration**

* ** [Web Technologies](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model) (DOM Analysis & HTML/CSS):** Expertise in inspecting the Document Object Model (DOM) and validating frontend structure to ensure seamless element locators and UI integrity.
* ** [API Testing](https://www.postman.com/) (Postman & Newman):** Ensures contract compliance and data integrity through automated BDD snippets and environment-driven architecture.
* ** [Automation Roadmap](https://playwright.dev/) (Playwright & JavaScript):** Currently scaling into **Full-Stack Automation** using Playwright for high-speed, resilient end-to-end test suites (Current Focus 🚀).
* ** [Healthcare Domain](https://www.hl7.org/fhir/overview.html) (FHIR/HL7 Standards):** Specialized in Contract Validation and Clinical Logic verification for high-stakes health-tech environments.
* ** [Logic & Data Validation](https://json-schema.org/) (JSON Schema & SQL):** Validates system resilience against malformed or malicious inputs by enforcing strict data structure audits.
* ** [Quality Operations](https://www.atlassian.com/software/jira) (Jira, Trello, TestRail):** Streamlines the SDLC through professional Root Cause Analysis (RCA), defect tracking, and clear traceability.
* ** [Infrastructure & CI/CD](https://github.com/features/actions) (GitHub & Actions):** Manages version control and basic pipeline integration to support continuous deployment and delivery.

### **Core Competency Matrix**
| Category | Tools & Technologies | Strategic Value |
| :--- | :--- | :--- |
| **Languages** | JavaScript (ES6+), Markdown, JSON, SQL | Provides the programmatic foundation for advanced test logic and modern automation scripts. |
| **Methods** | Agile, Scrum, Risk-Based Testing (RBT) | Optimizes team dynamics and ensures testing is prioritized by business and technical risk. |
| **Collaboration** | Notion, Trello, AI-Assisted QA | Leverages **AI Collaboration** for test data generation, logic optimization, and documentation efficiency. |

<br>
  
---

## ## 🎯 Technical Audits & Frameworks

## **🏥 [NHS Patient Demographics Service (PDS) API Audit](https://github.com/santiagodiazola/nhs-pds-api-audit)**
**Technical Audit of the UK’s [National Healthcare](https://www.england.nhs.uk/) Data Infrastructure.**

* **The Challenge:** Assessing the resilience of a high-stakes API responsible for millions of patient records against non-standard "human-error" inputs and malformed data.
* **Key Technical Achievement:** Identified a critical **P1 Security Vulnerability** (500-level Internal Server Error) through systematic **Input Sanitization Fuzzing**.
* **Engineered Impact:** Mitigated potential **Denial of Service (DoS)** risks by providing remediation strategies for [FHIR-compliant](https://www.hl7.org/fhir/overview.html) validation middleware.
* **Audit Architecture:** Designed a decoupled **Postman/Newman framework** utilizing collection-level inheritance.
    * Implemented **Dynamic GUID Traceability** to ensure 100% unique transaction auditability.
    * Automated **JSON Schema validation** to enforce strict contract compliance.
 
  ![NHS PDS Postman Runner](https://github.com/santiagodiazola/nhs-pds-api-audit/blob/main/evidence/BUG-001.gif)

  <br>
---

## **🏢 [Hilton Honors - End-to-End Web Quality Audit](https://github.com/santiagodiazola/hilton-mendoza-qa-audit)**
**Manual Validation of Global Reservation & i18n Workflows.**

* **The Challenge:** Auditing complex booking logic and internationalization (i18n) across high-traffic hospitality endpoints to ensure global accessibility.
* **Traceability & Rigor:** Managed 11+ high-priority cases using **Equivalence Partitioning** and **Boundary Value Analysis** (See Notion Suite above).
* **[Critical Finding BUG-001](https://github.com/santiagodiazola/hilton-mendoza-qa-audit/blob/main/documentation/bug-report/BUG-001%20Registration%20Failure.pdf):** Identified a terminal i18n blocker via **Network/Console Inspection** that prevented account creation for global users.
* **Audit Architecture:**
    * Managed the full test lifecycle (Design → Execution → Defect Logging) using **[TestRail](https://github.com/santiagodiazola/hilton-mendoza-qa-audit/blob/main/documentation/TestRail/Hilton_Honors_QA_Audit_Summary_Report_Santiago_Diaz.pdf)** and **[Trello](https://trello.com/b/OpY0J1nf/qa-portfolio-bug-tracking)**.
    * Developed a **Requirements Traceability Matrix** to ensure 100% coverage of core booking flows (Search, Reservation, and Authentication).
    * Conducted **Heuristic Evaluation** and **Exploratory Testing** to identify logic gaps in guest capacity and session management.

![Bug Evidence](https://github.com/santiagodiazola/hilton-mendoza-qa-audit/blob/main/evidence/Evidence%20BUG-001.png)
*Console evidence showing a JavaScript execution failure in the registration module when processing non-standard UTF-8 characters (e.g., "í").*

---

### ##👨🏻‍💻 Professional Outlook

* **Communication:** Fluent English (Professional Level).
* **Location:** Remote-Ready / Global Collaboration.
* **Goal:** Engineering resilience into software to survive the real-world complexity of the end-user journey.

---

### ## 🎨 Outside the Terminal

When I’m not auditing APIs or building test suites, you’ll find me:
* 🎸 Playing **Jazz and Blues** on my Ibanez AF75.
* 🧶 **Tufting** handmade rugs and exploring textile design.
* 🏠 Managing an **Airbnb** in the mountains of Mendoza, Argentina.
* ⚽ Following **Argentine Soccer** (Godoy Cruz & River Plate).

---

### ## 📫 Let's Connect
* **LinkedIn:** www.linkedin.com/in/santiagodiazola

* **Portfolio:** [Link to your Notion or Website]

> *Quality is a mindset, not a department.*

---
