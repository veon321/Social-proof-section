# Frontend Mentor - Social proof section solution

This is a clean, responsive, and modern solution to the Social proof section challenge on Frontend Mentor.

## Links

- **Solution URL:** [https://github.com/veon321/Social-proof-section](https://github.com/veon321/Social-proof-section)
- **Live Site URL:** [https://veon321.github.io/Social-proof-section/](https://veon321.github.io/Social-proof-section/)

## Built with

- **Semantic HTML5 markup** (including `<main>` wrapper, proper header text hierarchy, and isolated review/profile blocks)
- **CSS Custom Properties (Variables)** for strict adherence to the design system's color scheme and unified font handling
- **Flexbox layout** for multidirectional alignment (main layout structure, staggered rating rows, and horizontal profile distribution)
- **Modern CSS Math Functions (`clamp()`)** for completely fluid typography, adaptive layout gaps, and dynamic component sizing
- **Google Fonts** (League Spartan)

## Features

- **Advanced Multi-Asset Background:** Implements a layered `background-image` technique on the body to handle two separate design SVGs (`bg-pattern-top` and `bg-pattern-bottom`), placing them dynamically via directional positioning without interfering with the centered content.
- **Fluid Typography & Adaptive Gaps:** Main font sizes and section gaps utilize `clamp()` logic to seamlessly scale across mobile viewports and large desktop screens without rigid breakpoint snap-points.
- **Asymmetric Staggered Layout:** Leverages pure Flexbox positioning (`align-self: flex-start / center / flex-end`) to create the distinctive staggered "staircase" layout for the review blocks, and absolute coordinate offsets (`transform: translateY()`) to step the testimonial profile cards vertically.
- **Viewport Height Containment Fix:** Employs `min-height: 100vh` on the root container combined with a responsive media query override (`align-items: flex-start` on mobile) to guarantee the component remains centered on desktops while remaining fully scrollable and preventing top-overflow on smaller viewports.
- **Clean Flexbox Distribution:** Replaces fixed-width boundaries with fluid `flex: 1` allocations on the user testimonial cards, allowing the textual content to distribute itself proportionally with clean internal line heights.
