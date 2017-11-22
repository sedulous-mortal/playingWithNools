# Playing Tic-Tac-Toe with Nools

### Learn Nools the fun way. 

### Nools is a rules engine for node, based on the rete network. Nools are an alternative to Drools, using Node/Javascript for rules instead of Java and .drl files (Drools Rule Files).

Note: Nools are currently deprecated and unsupported but are useful as a learning tool at a minimum. This example is built as a revision over the original [nools github repo](https://github.com/noolsjs/nools), in the [examples/sudoku](https://github.com/noolsjs/nools/tree/master/examples/sudoku) folder. There is also a [repo](https://github.com/noolsjs/sudoku-example) that is an isolated Sudoku example by noolsjs, if that's something of interest to you.

### Installation

1) Clone the repo.  

`git clone https://github.com/sedulous-mortal/playingWithNools.git`

2) cd into 'sudoku' folder. 
	`cd sudoku`

3) `npm install`

4) run `node index.js` 
This creates the grid and fills in the given numbers, but it also lists in the empty cells the possibilities for those cells. 

5) If you want to, you can make the nools solve the puzzle it created (and list its reasoning!) by running `solve()` once you have the `sudoku>>` prompt in your console.

6) To exit the interface, you need to CTRL+C twice, or CTRL+C once and then type `.exit()`