This repository documents my in-depth study of Object-Centric Process Mining (OCPM), aimed at building a solid foundation for my Master's thesis research. This journal tracks my entire journey, from core theoretical concepts to hands-on implementation, guided by the "Process Mining Research Preparation" course provided by my supervisor.

Learning Objectives
To gain a deep understanding of OCPM's core theory, especially how it resolves the convergence and divergence issues in traditional process mining.   

To achieve proficiency in applying core Python libraries like pm4py and ocpa for OCPM analysis.

To master research methodologies, including model quality evaluation and process simulation using tools like CPN Tools.

To conduct end-to-end analysis on real-world datasets and develop a well-founded research proposal.

Current Progress (As of Early August 2025)
Core Papers: Have completed reading "Object-Centric Process Mining: Dealing With Divergence and Convergence in Event Data" and the "OCEL (Object-Centric Event Log) 2.0 Specification".   

Online Coursework: To supplement my learning, I have enrolled in the RWTHx edX course on OCPM, and focus on completing the modules up to Week 2: Process Models.
Progress:

[x] Week 1: Introduction to Process Mining, Completed section (Completed on 25/07)

[x] Week 2: Process Models, Incomplete section (Completed on 02/08)

[x] Week 3: Comparing Process Models, Incomplete section (Completed on 05/08)

[ ] Week 4: Process Discovery 1, Incomplete section

[ ] Week 5: Process Discovery 2, Incomplete section

[ ] Week 6: Conformance Checking, Incomplete section

[ ] Week 7: Beyond Control Flow, Incomplete section

[ ] Week 8: Link to Machine Learning, Incomplete section

[ ] Week 9: Outlook and Closure, Incomplete section

[ ] Final Exam

Hands-on Practice: I am actively applying the concepts learned by exploring and testing datasets on the Celonis platform.

Next Step: My immediate plan is to structure all my learning activities and outputs according to the new "Process Mining Research Preparation" course outline below.

Learning Plan (Following the "Process Mining Research Preparation" Course)
My study is structured around the sections of the thesis preparation course.

Section 1: Introduction to Object-Centric Process Mining
Goal: Understand the motivation, key data formats (OCEL, EKG), and discovery principles of OCPM.

Tasks:

[x] Read: Object-Centric Process Mining: Dealing With Divergence and Convergence...    

[x] Read: OCEL 2.0 Specification.

[ ] Read: Papers on Event Knowledge Graphs (EKG) and OCED.

[ ] Read: Paper on OCPQ (Object-Centric Process Querying).

Deliverable:

[x] Create and maintain this GitHub repository to document my work with OCEL using pm4py and ocpa, ensuring reproducibility.

Section 2: Object-Centric Process Discovery
Goal: Differentiate between and discover various OCPM models (OCDFG, OCPN, OCCN) and learn how to evaluate their quality.

Tasks:

[ ] Read: Discovering object-centric petri nets.   

[ ] Read: Object-Centric Causal Nets.   

[ ] Read: Discovering Compact, Live and Identifier-Sound... Models.

Deliverable:

[ ] Literature Review & Reference Table: Create a table mapping discovery algorithms (e.g., OCPN in PM4Py, OCPN in OCPA) to their supported evaluation measures (Fitness, Precision, etc.), citing the relevant sources.

Section 3: Applied Research
Goal: Brainstorm and frame a practical, real-world research idea.

Tasks:

[ ] Explore applied OCPM research in domains of interest (e.g., finance, e-commerce, healthcare).

[ ] Identify potential open datasets or define a simulation scenario.

Deliverable:

[ ] Idea Proposal (1–2 pages): Propose a domain and process to analyze, identify the object types, and describe the planned approach (open data vs. simulation).

Section 4: Fundamental Research (Optional Track)
Goal: Explore the potential for developing new algorithms or theoretical models.

Tasks:

[ ] Conduct a deep literature review to identify a research gap.

[ ] Formalize a new model or algorithm.

Deliverable:

[ ] Prototype Implementation: Develop a working prototype in Python and document it in a dedicated repository.

Section 5: Simulating Object-Centric Event Logs
Goal: Master process simulation using CPN Tools to generate high-quality, realistic OCELs for evaluation.

Tasks:

[ ] Learn the basics of CPN Tools and Standard ML (SML).

[ ] Analyze provided sample models (Order Management, Container Logistics).

Deliverable:

[ ] Design and Simulate an OCEL: Create a Colored Petri Net in CPN Tools that generates an OCEL file, adhering to specific temporal constraints (e.g., Swedish working days/hours).

Project Log & Implementations
This section links to the practical work and deliverables produced during my study.

Notebook 01:(./notebooks/01_OCEL_Analysis_with_Selected_Dataset.ipynb)

Status: In Progress

Summary: Loading a selected OCEL dataset (e.g., from BPI Challenge) to perform initial analysis and discover the first Object-Centric Petri Net (OCPN) using pm4py. This directly corresponds to the deliverable for Section 1.

Notebook 02:(./notebooks/02_Model_Evaluation_with_Selected_Dataset.ipynb)

Status: Planned

Summary: Applying ocpa to evaluate the discovered model's fitness and precision. This will form the basis for the reference table required in Section 2.

Notebook 03:(./notebooks/03_Comparative_Analysis_with_Second_Dataset.ipynb)

Status: Planned

Summary: Applying the full analysis pipeline to a second, different dataset to test the generalizability of the methods.

Tech Stack & Tools
Languages: Python, SQL

Core Libraries: pm4py, ocpa, pandas, matplotlib

Platforms & Tools: Jupyter Notebook, Git, GitHub, Celonis, CPN Tools (planned)
