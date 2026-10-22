# Modeling Software Architecture

*Communicate system structure, behavior, and trade-offs with C4, viewpoints, and perspectives*

Companion repository for **Modeling Software Architecture** by **Ilya Hardzeenka**. Here you can explore the book's figures, open editable diagrams, and examine the complete marketing-system model built throughout the chapters.

The book shows how to create connected architecture views that answer questions for different audiences. One continuous marketing-system case study connects business functions, system structure, data, operational processes, concurrency, development, and deployment. Architecture perspectives then help evaluate concerns that span those views.

**Start with the [chapter figures](#chapter-figures), explore the [marketing-system model](#marketing-system-model), or learn [how to open the diagrams](#open-and-edit-the-diagrams).**

## Who this book is for

Software architects, engineers, developers, technical leads, engineering managers, consultants, CTOs, product owners, and business analysts who need to understand, explain, design, or evolve software systems.

A basic understanding of software systems is sufficient. No prior experience with C4 or architecture modeling is required.

## What you'll learn

- Choose views, abstraction levels, and notation to suit a question and its audience.
- Combine C4 with viewpoints and perspectives to build a consistent architecture model.
- Connect functions, components, data, processes, delivery paths, and infrastructure.
- Evaluate cross-cutting concerns, identify risks, and discuss design trade-offs.
- Document decisions, version diagrams, and keep architecture models current.

## Explore the repository

### Chapter figures

Each chapter folder contains its figures, including progressive versions that show how the model develops. File names follow the figure numbering in the book; for example, `chapter-07/figure-7.01.drawio.png`.

**Part 1: Foundations of Software Architecture Modeling** introduces models, visual communication, abstraction, frameworks, notation, documentation, and version control.

| Chapter | Figures |
| --- | --- |
| 1. Visualizing Systems | [chapter-01](chapter-01/) |
| 2. Modeling Software Architecture | [chapter-02](chapter-02/) |
| 3. Architecture Frameworks and Notations | [chapter-03](chapter-03/) |
| 4. Diagramming, Documentation, and Version Control | [chapter-04](chapter-04/) |

**Part 2: Modeling Architecture with Viewpoints, Perspectives, and C4** applies those foundations to the marketing system, building connected views and evaluating the completed model.

| Chapter | Figures |
| --- | --- |
| 5. Understanding the Marketing Domain | [chapter-05](chapter-05/) |
| 6. Functional Viewpoint: Modeling Functions and Business Processes | [chapter-06](chapter-06/) |
| 7. Context Viewpoint: Defining Structure Using the Core C4 Model | [chapter-07](chapter-07/) |
| 8. Information Viewpoint: Modeling Data Structures and Flows | [chapter-08](chapter-08/) |
| 9. Operational Viewpoint: Connecting Functions, Components, and Data | [chapter-09](chapter-09/) |
| 10. Concurrency Viewpoint: Modeling Parallel Processing and Scalability | [chapter-10](chapter-10/) |
| 11. Development Viewpoint: Organizing Code, Repositories, and Delivery | [chapter-11](chapter-11/) |
| 12. Deployment Viewpoint: Mapping Components to Infrastructure | [chapter-12](chapter-12/) |
| 13. Architecture Perspectives: Evaluating Cross-Cutting Concerns | [chapter-13](chapter-13/) |

### Marketing-system model

The [marketing-model](marketing-model/) folder brings together the seven completed viewpoints. Open them to review how the views fit together and adapt parts of the model for your own projects.

| Viewpoint | Model |
| --- | --- |
| Functional | [Functions and business processes](marketing-model/01.functional-viewpoint.drawio.png) |
| Context | [System structure](marketing-model/02.context-viewpoint.drawio.png) |
| Information | [Data structures and flows](marketing-model/03.information-viewpoint.drawio.png) |
| Operational | [Functions, components, and data in sequence](marketing-model/04.operational-viewpoint.drawio.png) |
| Concurrency | [Concurrent processing](marketing-model/05.concurrency-viewpoint.drawio.png) |
| Development | [Code, repositories, and delivery](marketing-model/06.development-viewpoint.drawio.png) |
| Deployment | [Components and infrastructure](marketing-model/07.deployment-viewpoint.drawio.png) |

The [practice](practice/) folder contains additional viewpoint diagrams organized into introduction, mechanics, and presentation files.

## Open and edit the diagrams

Most figures use the `.drawio.png` format, which combines a PNG image with an embedded, editable draw.io diagram.

- **View a figure:** open it on GitHub or download it and use an image viewer. Enlarge detailed diagrams to inspect labels and relationships.
- **Edit a diagram:** download the original `.drawio.png` file, open [draw.io](https://app.diagrams.net/), choose **File → Open From → Device**, and select the file. You can also use the draw.io desktop application.

## Work through the exercises

Read the chapters in sequence: each viewpoint reuses information and decisions from earlier chapters. In Chapters 6–12, complete the *Try it yourself* exercises before looking at the finished diagrams.

1. Review the viewpoint's purpose, inputs, notation, and modeling rules.
2. Make your first attempt using the information available at that point. Selected chapter figures provide starting points for the exercises.
3. Follow the progressive figures and examine the reasoning behind each addition.
4. Complete the second exercise, then compare your work with the completed viewpoint and check its consistency with earlier views.

Use your preferred modeling tool, a whiteboard, or paper. No particular programming language, operating system, or cloud account is required.
