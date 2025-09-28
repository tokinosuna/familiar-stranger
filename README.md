# Familiar Stranger: An Accessible Simulation of Workplace Isolation

## What Inspired Me
This project was born from the deeply personal experience of navigating a workplace as a "familiar stranger"—the person who is physically present, but functionally invisible. It's a feeling many people know, whether they're third-culture kids, neurodivergent, or simply don't fit into a pre-existing, tight-knit social structure. You're a ghost in the machine, performing tasks in a vacuum while life happens in a group chat you're not in.

I was inspired to turn this experience into a game to answer a few questions:
- How can you quantify the slow, draining cost of daily social exclusion?  
- What if you could contrast this reality with the ideal, inclusive onboarding experience everyone deserves?  
- Could a game make this invisible struggle tangible and foster empathy in those who have never experienced it?  

This led to the creation of a **dual-narrative game**:
- The **"Dream Office"** is a pastel-colored world of support and inclusion.  
- The **"Familiar Stranger"** is its Y2K-themed, glitchy, and isolating counterpart, based on my real-life experiences.  

---

## Accessibility as a Core Theme and Feature
For the Hacks4Access hackathon, accessibility was the primary driver. This project approaches it on two levels:

### Thematic Accessibility
The game's main goal is to make the often-invisible challenges of social anxiety, workplace trauma, and exclusion **accessible and understandable**. It simulates the mental and emotional energy ("Social Battery") required to navigate these environments, turning an abstract concept into a measurable game mechanic.

### Functional Accessibility
The game itself is built to be inclusive:
- Simple, clean UI  
- High-contrast and large-text modes (toggled on the fly)  
- Settings saved locally so the user's needs are remembered  
- Entirely self-contained in a **single HTML file**, accessible on any modern web browser without complex setup  

---

## How I Built It
This project was built from the ground up using a **"vanilla" stack**: pure HTML, CSS, and JavaScript (ES6). I intentionally avoided frameworks to keep the project lightweight, transparent, and to challenge myself.

- **Dual-Narrative Engine**: A state-management object (`gameFlags`) tracks progress and encountered events, creating a persistent world where choices and time matter.  
- **Dynamic Event System**: "Event pools" for different times of day keep each run unique, while still advancing the overall narrative.  
- **Contrasting UI/UX**:  
  - **Dream Office** → Inter font + pastel palette, soft and welcoming.  
  - **Familiar Stranger** → VT323 pixel font + Windows 95 color scheme, vaporwave-inspired background, evoking nostalgic alienation.  

---

## Challenges I Faced
The biggest challenge was translating nuanced, often painful personal experiences into a game without it becoming overly deterministic.  

- I wanted to avoid creating a "pity simulator"—instead, I aimed for an **empathetic tool**.  
- Balancing harsh realities with **moments of agency and small victories** (e.g., energy boosts from personal projects) was key.  
- On the technical side, managing complex event flags and branching paths in pure JavaScript required careful planning to remain manageable and bug-free.  

---

## What I Learned
- **Game mechanics** can be a powerful tool for **empathy**.  
- Quantifying something as abstract as "social energy" makes people see familiar situations in new ways.  
- On the technical side, this project reinforced the **power of vanilla JS** and the importance of designing for **accessibility from the very beginning**, not as an afterthought.  

---

## Built With
- **HTML5**  
- **CSS3**  
- **JavaScript (ES6+)**  

_No frameworks, no libraries—just pure, foundational web technologies._

---

## "Try it out" Links
- **Live Demo**: [Link to your live game hosted on GitHub Pages, Netlify, etc.]  
- **GitHub Repository**: [Link to your GitHub repo]  

---

## Additional Info (For Judges and Organizers)

### Inspiration
My inspiration came directly from my own experiences as an apprentice in a company with a very closed, pre-established social circle. I wanted to explore the concept of being a "familiar stranger" and the silent emotional toll of being systematically, if not maliciously, excluded.  

The project aims to:
- Simulate the feeling of being an outsider  
- Contrast it with an idealized, inclusive environment  
- Highlight what's lost—and what's possible—in workplace culture  

It's a story for anyone who has ever felt like a ghost in their own office.

---

### What it Does
**Familiar Stranger** is an interactive narrative game where the player steps into the shoes of a new apprentice navigating a complex office social structure.

#### Core Mechanic
- Manage a **"Social Battery"**, which depletes with awkward or negative interactions and replenishes with peace or genuine connection.  
- The goal: **survive the workday.**  

#### Dual Modes
- **Dream Office** → idealized, supportive onboarding experience  
- **Familiar Stranger** → realistic simulation of workplace isolation, with branching storylines based on real events  

#### Accessibility Features
- Large Text mode  
- High Contrast mode  
- Built-in, easily accessible options  

#### Impact
By gamifying the experience of social exclusion, the project aims to **build empathy** and raise awareness of the **invisible barriers** that affect mental well-being and inclusion in professional settings.
