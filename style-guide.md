# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Very dark blue (main background): hsl(233, 47%, 7%)
- Dark desaturated blue (card background): hsl(244, 38%, 16%)
- Soft violet (accent): hsl(277, 64%, 61%)

### Neutral

- White (main heading, stats): hsl(0, 0%, 100%)
- Slightly transparent white (main paragraph): hsla(0, 0%, 100%, 0.75)
- Slightly transparent white (stat headings): hsla(0, 0%, 100%, 0.6)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 700

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400


body{
    background-color: var(--very-dark-blue);
    display: grid;
    min-height: 100vh;
    font-size: 0.938rem;
    color: var(--neutral-200);
    font-weight: var(--fw-regular);
    font-family: var(--ff-basic);
  }

  .container{
    color:var(--neutral-200);
    display: grid;
    place-content: center;
    min-height: 100vh;
    
    
  }
  .header{
    font-weight: var(--fw-bold);
    
  }
  .mini_text{
    color: var(--violet);
  }
  .card__stats{
    text-transform: capitalize;
    display: flex;
    flex-direction: column;
  }