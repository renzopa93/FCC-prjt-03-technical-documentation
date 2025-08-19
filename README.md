# Campsite Survey Form - Technical Documentation –  FreeCodeCamp Project

This is my third project from the Responsive Web Design certification at freeCodeCamp.
It documents my Campsite Survey Form project and focuses on clear structure, a left
sidebar navigation, and responsive behavior using only HTML and CSS.

## Features

- Semantic documentation layout using `nav`, `main#main-doc`, and multiple `section.main-section` blocks with `header` titles
- Left sidebar navigation with fixed positioning and a sticky navbar header that stays visible while you scroll the links
- In-page anchor links that jump to each documentation section
- Responsive design with media queries at 768px, 480px, and 320px
  - Navbar width and content spacing adjust per breakpoint
  - Table in the Project Structure section is wrapped in `.table-container` and scrolls horizontally on narrow screens to remain readable
- Inline code styling via the `code` element for technical terms
- Cohesive visual theme (forest green, warm beige) and readable typography (Merriweather)

## Live Demo

See it live: [Technical Documentation Page](#)

## What I Learned

- How to structure a technical documentation page with semantic HTML (`nav`, `main`, `section`, `header`) and meaningful sectioning
- How to build a left sidebar navigation using fixed positioning and keep the navbar header visible using `position: sticky`
- How to create responsive layouts with targeted media queries (768px, 480px, 320px) that:
  - Adjust the navbar width and content spacing
  - Keep tables usable on small screens by isolating overflow to a scrollable container
- How to avoid full-page horizontal scrolling by confining overflow to the table wrapper instead of the entire page
- How to enhance readability with consistent spacing, headers, and inline `code` styling

## Personal Note

This project helped me move from building a single survey form to documenting a project clearly and accessibly. I’m particularly proud of the fixed sidebar with a sticky header and the responsive refinements that make the page comfortable to use on phones without breaking the layout. Debugging the horizontal scroll issue taught me to isolate overflow to specific components (like tables) rather than the whole page.

## Technologies Used

- HTML5
- CSS3
- Responsive CSS techniques: media queries (768px, 480px, 320px), fixed and sticky positioning, and overflow containment with `.table-container`


