[L_TOC_11
# Setting the standard
The team is to agree on a standard for how we document and design architectural diagrams.
- What is the current level expectation of
- How do we provide
that tell the narrative for different stakeholders?
- How do we ensure documentation and diagrams are dynamic/flexible?
- How do we ensure visual consistency?
- Does the chosen approach fit the team's vision, goal, and objectives?
- How do we move fast as a team?
- How do we communicate quickly and well?
Considerations :
- [Diagram considerations ]https://c4model.com/review/) - Does this approach fit the objective?
# What is the C4 Model?
The C4 Model is an "abstraction-first" approach to diagramming software architecture
C4 stands for:
1. Context
2. Containers
3. Components
4. Code
**NOTE :**
_The definition of containers has no relationship to Docker-_
# C4 Model breakdown
## Content / System Context (Level 1)
System Content is the system mapping plus user and system dependencies at a high level.
When drawing a system context diagram we need to be thinking or asking "Who's using it?" Is it a particular Role or User(s), assess the persona(5). Then we are able to map the user alongside nonspecific technology systems.
[Video breakdown of System Content] (https://youtu.be/x2-rShpw0g?t=691)
<br></br>
## Containers (Level 2)
The container level is the overall shade of the architecture and chosen technologies.

<br></br>
## Containers (Level 2)
The container level is the overall shape of the architecture and chosen technologies.
As Developers, Architects and Engineers, we will require further detail of our proposed/current solution(s)
We should aim to cover
- Applications
- Data Stores
- how they connect at runtime
- Technologies they are built on
- Application responsibilities.
In the Level 2 Container diagram, We should still see people and external systems dependencies.
[Video breakdown of Containers ](https://youtu.be/x2-rShpw0g?t=827)
<br></br>
## Components (Level 3)
At the Component level, we display the Logical components and their interactions within a container.
We show the low-level technology choices. These should reflect code structure at a high level of a 1-2-1 mapping of code concepts to diagram concepts.
[A video breakdown of Components ](https://youtu.be/x2-rShpwog?t=1021)
[image.png](/ attachments/image-c8e05458-7d6-4439-aec6-72280d244e2c.png)
_placeholder_
<br></br>
Here is a full video of the C4 Model -
>[Full Video] (https://www.youtube.com/watch?v=x2-rShpwog&t=288s) _35:32_
# Notations
Notations should contain the following:-
#* Titles on pictures/diagrams
› Titles should be short and meaningful. Provide a diagram type and number the diagram if the order is important.
### Visual Consistency
> Aim to be consistent with notation and element positioning.
### Acronyms
› Careful consideration of the usage of acronyms, especially those unique to the business/domain.