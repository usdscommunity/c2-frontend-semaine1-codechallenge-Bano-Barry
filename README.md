# Frontend Mentor - Huddle landing page with single introductory section solution

![Design preview for the Huddle landing page with single introductory section](./design/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Desktop Design](./design/desktop-design.jpg)
![Mobile Design](./design/mobile-design.jpg)
![Active States](./design/active-states.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/Bano-Barry/c2-frontend-semaine1-codechallenge-Bano-Barry)
- Live Site URL: [GitHub Pages](https://bano-barry.github.io/c2-frontend-semaine1-codechallenge-Bano-Barry/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- CSS Flexbox
- Mobile-first workflow
- Google Fonts (Poppins & Open Sans)
- Font Awesome icons

### What I learned

Ce projet m'a permis de mettre en pratique plusieurs concepts importants :

1. **CSS Grid pour la mise en page principale** : J'ai utilisé CSS Grid pour créer une mise en page responsive en deux colonnes sur desktop.

```css
.content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    align-items: center;
}
```

2. **Transitions et états de survol** : J'ai ajouté des effets de transition fluides pour améliorer l'expérience utilisateur.

```css
.cta-button:hover {
    background-color: hsl(300, 69%, 71%);
    color: white;
    transform: translateY(-2px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
}
```

3. **Design responsive** : J'ai implémenté une approche mobile-first avec des media queries pour adapter la mise en page.

```css
@media (max-width: 768px) {
    .content {
        grid-template-columns: 1fr;
        text-align: center;
    }
}
```

### Continued development

Dans mes futurs projets, je souhaite continuer à améliorer mes compétences en :

- Animations CSS plus avancées
- Optimisation des performances
- Accessibilité web (ARIA, navigation clavier)
- CSS Grid et Flexbox pour des mises en page complexes

## Author

- Name - Bano Barry
- Frontend Mentor - https://github.com/usdscommunity | Leads FrontEnd
- GitHub - [@Bano-Barry](https://github.com/Bano-Barry)

## Acknowledgments

Merci à Frontend Mentor pour ce challenge qui m'a permis de pratiquer mes compétences en développement front-end dans un contexte réaliste.