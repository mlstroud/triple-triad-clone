# _Triple Triad Clone_

#### By _**Matt Stroud**_
##### _Last Updated April 14, 2020_

## Description

_This is a clone of the Triple Triad card game from Final Fantasy VIII._  
_Original cards are not used and dummy ones were created to prevent using copyrighed game assets._

## Technology
* JavaScript & jQuery
* Webpack
* Node Package Manager
* Bootstrap
* HTML & CSS

## Specs
| Behavior                                                                                               | Input                         | Output                                |
|:-------------------------------------------------------------------------------------------------------|:------------------------------|--------------------------------------:|
| The program flips a coin to decide who goes first.                                                     | N/A                           | Heads. Player 1 goes first.           |
| The program allows the first player to place a card on the 3x3 grid.                                   | Place card on middle square.  | Board displays card on middle square. |
| The program will "flip" adjacent cards if weaker than the card placed next to them.                    | Card(A) placed by Card(9).    | Card(9) is flipped.                   |
| The program will not "flip" the played card if placed next to a stronger card.                         | Card(3) placed by card(6).    | Nothing happens.                      |
| The program will update scores when a card is flipped.                                                 | Player 1 flips Player 2 Card. | Score 5-5 => 6-4                      |
| The program will end the game once all 9 positions have been played, and display result.               | Score 7-3                     | Player 1 Wins                         |
| The program will allow the winner to take one card from the loser's hand and store in their inventory. | Select Grunt Card.            | Player 1 now owns Grunt Card.         |


## Stretch Goals
* N/A

## Known Bugs
* N/ A


## Setup/Installation Requirements

* Clone this repository.
```
git clone https://github.com/mlstroud/triple-triad
```
* Install the required dependencies and plugins.
```
npm install
```
* Build the project and start the development server.
```
npm run start
```
* _Note: If you are on Mac, open the package.json file and make the following change before running the above command:_  
```
npm run build & webpack-dev-server --open --mode development
```
**change to**
```
npm run build; webpack-dev-server --open --mode development
```

## View Online

* N/A

### License

This software is licensed under the MIT license.

Copyright (c) 2020 **Matt Stroud**