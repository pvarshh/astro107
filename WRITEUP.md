# Project Write-Up: The Interstellar Traveler’s Guide to Black Holes

- **Student Name:** Pranav Varshney
- **Date:** December 2, 2025

---

# Submission Sources

- [https://github.com/pvarshh/astro107](https://pvarshh.github.io/astro107/)
- [https://pvarshh.github.io/astro107/](https://pvarshh.github.io/astro107/)

---

## 1. Project Overview
For this assignment, I created an interactive website titled **"The Interstellar Traveler’s Guide to Black Holes."** Instead of a standard textbook explanation, the site is framed as a digital safety brochure for future space tourists. The user navigates through sections like "Safety Warnings," "Sightseeing," and "What to Pack," encountering accurate physics concepts disguised as travel tips.

This format allowed me to explore the "weirdness" of black hole physics—such as time dilation and spaghettification—in a way that is intuitive and engaging for a general audience.

---

## 2. Incorporated Black Hole Concepts
Per the assignment requirements, I have incorporated several key Black Hole concepts as integral parts of the website. If these concepts were removed, the "travel guide" would lose its internal logic and scientific basis.

### A. The Event Horizon & Escape Velocity
*   **Concept:** The Event Horizon is the boundary where the escape velocity equals the speed of light ($c$). Since nothing can travel faster than light, nothing can escape.
*   **Implementation:** In `safety.html`, this is presented as the ultimate "Do Not Cross" line. The warning explicitly states that once you cross, you cannot send a distress signal because the signal itself cannot escape.

### B. Schwarzschild Radius ($R_s$) & Mass
*   **Concept:** The physical size of the event horizon (the Schwarzschild Radius) is directly proportional to the black hole's mass ($R_s = 2GM/c^2$).
*   **Implementation:** The guide distinguishes between **Stellar-Mass** and **Supermassive** black holes. I explain that while all black holes have an event horizon, their size and the tidal forces you experience near them depend heavily on their mass.

### C. Gravitational Time Dilation
*   **Concept:** Time passes slower closer to a massive object (deep in the gravity well) relative to an observer far away.
*   **Implementation:** In `packing.html`, this is humorously presented as a "packing tip." Travelers are told they don't need a watch because it will tick too slowly compared to Earth. I also reference the "Twin Paradox," explaining that a short trip for the traveler could mean decades pass for their friends on Earth.

### D. Gravitational Redshift & Doppler Beaming
*   **Concept:** Light loses energy (becomes redder) as it climbs out of a gravity well. Additionally, material moving towards an observer appears brighter and bluer (Doppler Beaming).
*   **Implementation:**
    *   **Redshift:** Listed as a reason to bring a "Redshift Filter" for cameras in the packing list.
    *   **Doppler Beaming:** In `sightseeing.html`, I explain why the Accretion Disc is asymmetric (brighter on one side) using the Doppler effect.

### E. The Accretion Disc
*   **Concept:** Matter falling into a black hole forms a flat, rotating structure that heats up due to friction.
*   **Implementation:** This is the main attraction of the "Sightseeing" page, described as a "ring of fire" glowing in X-rays.

---

## 3. Accuracy & Physics
While the tone is creative, the underlying physics is accurate:
*   **Spaghettification:** I correctly identified that tidal forces (the difference in gravity between head and feet) are the cause of spaghettification, and that these forces are actually *weaker* at the horizon of a supermassive black hole compared to a small one.
*   **The Photon Sphere:** I included the specific distance of $1.5 R_s$ where light orbits the black hole, allowing an observer to theoretically see the back of their own head.
*   **The Shadow:** I noted that the black hole's visual "shadow" is larger than the actual event horizon due to the bending of light.

## 4. Resources
The following credible sources were used to ensure scientific accuracy:
*   **NASA Science:** For definitions of the Event Horizon and Accretion Discs.
*   **Event Horizon Telescope (EHT):** For the M87* image and shadow size data.
*   **ESO (European Southern Observatory):** For visualizations of spaghettification.
*   **Class Notes:** For the specific formulas regarding Schwarzschild Radius and Time Dilation.

---

## 5. Conclusion
This project demonstrates that Black Holes, while terrifyingly complex, can be understood through the laws of General Relativity. By framing these laws as "rules of the road" for a traveler, I have shown how mass, gravity, and light interact to create the most extreme environment in the universe.
