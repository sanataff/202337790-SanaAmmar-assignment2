# AI Usage Report

**Student:** Sana Ammar  
**Student ID:** 202337790  
**Assignment:** SWE363 — Assignment 2 (Interactive Features)

## How I used AI

I used the OpenCode AI coding agent (DeepSeek V4.1 Flash) as a helper while
building this project. I asked it to help move my original portfolio from plain
HTML, CSS and JavaScript to React, Vite and TypeScript. It also helped me draft
components, styles, custom hooks and this documentation.

I reviewed the suggestions as I worked. I changed or removed parts that did
not fit the project, and checked the finished work with the 
production build.

## What AI helped me with

AI helped me plan how to split the site into components such as `Header`,
`About`, `Projects`, `Stack` and `Contact`. It also helped draft the
project search, filters and sorting, expandable cards, theme toggle, contact
form validation, and the hooks used for saved settings and scroll animations.

I also used it to work through TypeScript  errors and to create the
light and dark colour styles, responsive layouts and animations.

Some examples of the prompts I used:

- “Move my portfolio to React and TypeScript while keeping its content and
  simple design.”
- "create for me a panel on the web to help me experiment with different color combinations" 
- "create for me a panel on the web to help me experiment with different layout options" 
-" do not use gradients or heavy shadows in the design "
- “Help me understand and fix this TypeScript build error.”

## Benefits and challenges

AI helped me get a first version of the site in place faster and gave me a
useful way to think through how to organise the components. It was also helpful
when I needed an explanation for an error or wanted to compare possible
solutions.
It really helped with experimentation quickly, for example, I asked the LLM to give me web view panel where I can adjust colors and layout on the web so I can see the changes immediatly and decide quickly, it is like using figma, but in dev. 
It helped me create sophisticated components, like the "jump to top" component. 
It helped me integrate the ui component "darawbly"
It helped me experiment with different layouts and color combinations quickly 

The suggestions were not always right. For example, some names did not match
between files. I had to check the code, understand the issues and decide
what to change. AI also missed details that mattered to this project, such as
making it clear that the contact form does not actually send a message.


## Learning Outcomes 

- I learned how to break a larger React application into focused components and
  reusable hooks, and how to pass data and state between them in a way that
  keeps the code easier to maintain.
- I improved my understanding of TypeScript and React state by implementing
  interactive features such as project filtering, theme preferences and form
  validation, then checking that their behaviour matched the interface.
- I learned how to use AI more paragmatically, for example, asking ai for a big task and let it generate 10 files is a bad approch, I broke down the tasks into smaller ones and started doing them one by one with ai 
- I learnt how to use skills to enhance the outcomes of AI 


## Changes I made

I made the naming consistent across components and hooks. I removed an unused implementation and a
broken GitHub icon. I also changed the form confirmation so it does not imply
that a message was sent.

## How I checked the work

I ran `npm run build`.  I also checked how the interactive
features should behave, including project search and filters, theme
preferences, form validation and repository loading states. Finally, I
reviewed the layout at desktop and mobile widths.

AI suggestions were a starting point, not a substitute for my own decisions.
I reviewed the code I kept and can explain how the features work and how they
meet the assignment requirements.

## Commit history and AI assistance

The table below lists the commits on the `main` branch. “AI-assisted” identifies
commits related to the React/Vite rebuild and features described above. Git does
not record whether AI was used for an individual commit, so commits marked
“no AI-assistance” cannot be attributed reliably from the available history alone.
Generated agent-session checkpoints and local Git backup entries are not
included.

| Commit | Date | Commit message | AI assistance |
| --- | --- | --- | --- |
| `bf71481` | 2026-10-17 | add preview link to readme file | no AI-assistance |
| `331ccf3` | 2026-10-17 | Configure Netlify build | no AI-assistance |
| `a5598c0` | 2026-10-17 | update docs | AI-assisted documentation |
| `c7ef4b0` | 2026-10-17 | delete unused file | no AI-assistance |
| `f081768` | 2026-10-17 | fix project structure | AI-assisted rebuild |
| `2c634a1` | 2026-10-17 | Change small header style | no AI-assistance |
| `85b9fbe` | 2026-10-17 | remove unused code | no AI-assistance |
| `4ca111c` | 2026-10-17 | fix header | no AI-assistance |
| `ba70c7d` | 2026-10-17 | fix docs | AI-assisted documentation |
| `442a0dc` | 2026-10-16 | update doccs | AI-assisted documentation |
| `3a1b45e` | 2026-10-16 | delete unused files | no AI-assistance |
| `89c3cd7` | 2026-10-16 | add Projects and Stack components with filtering and sorting functionality | AI-assisted feature |
| `75cc8e3` | 2026-10-16 | add reveal components and hooks for scroll animations | AI-assisted feature |
| `7aaf80c` | 2026-10-16 | add custom hooks for localStorage management and theme persistence | AI-assisted feature |
| `8827b65` | 2026-10-16 | add BackToTop component and smooth scrolling helpers | AI-assisted feature |
| `51444df` | 2026-10-16 | add main application structure with components for About, Contact, Footer, Header, Projects, and Stack | AI-assisted rebuild |
| `43da508` | 2026-10-16 | update packages | AI-assisted rebuild |
| `890f807` | 2026-10-16 | config vite correctly | AI-assisted rebuild |
| `39efd17` | 2026-10-16 | delete unused files | no AI-assistance |
| `d321e85` | 2026-09-18 | edit docs | no AI-assistance |
| `98d0a14` | 2026-09-18 | add css styling for contact links | no AI-assistance |
| `f2c0a84` | 2026-09-18 | change font weight of paragraph | no AI-assistance |
| `26acba0` | 2026-09-18 | change font size from 15px to 16px | no AI-assistance |
| `07cd5d1` | 2026-09-18 | add docs | no AI-assistance |
| `72cd7ed` | 2026-09-18 | add social links | no AI-assistance |
| `fc32799` | 2026-09-18 | add contact form along with css stylilng | no AI-assistance |
| `d9eb9b4` | 2026-09-18 | add css styling for project section | no AI-assistance |
| `15ee036` | 2026-09-18 | add project section | no AI-assistance |
| `bc65cde` | 2026-09-18 | add css styling and responsiveness | no AI-assistance |
| `ba966fa` | 2026-09-18 | add intro section and about section alongside with styling | no AI-assistance |
| `684a1aa` | 2026-09-18 | chore: add required links to the header | no AI-assistance |
| `0adf753` | 2026-09-17 | chore: add files | no AI-assistance |
| `954d86e` | 2026-09-17 | Initial commit | no AI-assistance |

## signed declaration
I declare that this report and the attached evidence document all of my AI use in this assignment, with complete and unedited conversations, and that I understand and can explain all the code I submitted. I understand that undeclared AI use or a false declaration will be treated as plagiarism according to KFUPM regulations.
Full Name: Sana Ammar
Student ID: 202337790
Date: 10/16/2026
Signature: Sana