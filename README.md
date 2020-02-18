# signpost
A remake of the game Signpost by Simon Tatham.

Signpost is a puzzle game where users connect squares in a grid in order to create a path from beginning to end. Each square may only be connected to squares that are "queen moves" (any length in any cardinal or ordinal direction) away in the direction denoted by the square's arrow. The first (#1) and the last squares are fixed, and depending on the random game generator some other squares may be as well. Fixed squares must retain their numbering no matter what solution. Connections can be undone by dragging the arrow off the screen.

Variations of connections:
- A numbered square to a numbered square. This connection is only allowed if the squares' numbers are consecutive.
- A numbered square to an unnumbered square. The unnumbered square will take on a number one higher than the numbered. For example, if the numbered square is N, the unnumbered will be N + 1.
- An unnumbered square to an unnumbered square. Both squares will be part of the same group denoted by a letter. For example, the first square will be a, and the second a + 1.

Players are not required to solve the sequence in order. In fact, it may even be advisable to test out little groups in the middle of the sequence before connecting them to each other.
