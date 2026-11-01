# Assignment 6.4 - Positioning Practice

## Position Values Used

- sticky: the navigation bar scrolls with the page until it reaches top: 0, then it stays at the top of the screen.
- fixed: the Help button is placed relative to the browser window, so it stays at the bottom right even when the page scrolls.
- absolute: the New badge is placed using top and right values, relative to its nearest positioned parent.
- relative: the card has position: relative, which makes it the parent that the absolute badge is measured from. Without it, the badge would be placed relative to the whole page.

## z-index

z-index controls which element appears on top when elements overlap.

- Help button: 200 (highest, always on top)
- Navigation bar: 100 (stays above the page content when scrolling)
- Badge: 10 (above the card)