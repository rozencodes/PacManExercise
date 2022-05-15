# PacManExercise
<h2>Exercise goals:</h2>
- Coding PacMan to move across the screen and change direction once he hits a window border, moving back across the screen in a loop.

<h2>Challenges faced:</h2>
- For a while, I couldn't figure out why PacMan would not go across the whole window's screen and was stuck changing directions in the same spot the image originates. 

<h2>Fix:</h2>
- Once I placed the line: <em><strong>pageWidth = window.innerWidth;</strong></em> in the function <em><strong>checkPageBounds</strong></em>, PacMan moves across the screen and changes direction correctly.
