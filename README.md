# ticTactoe_in_swift

In this Project I made a Tic Tac Toe Game, below are the features of this game, and some implementation details

### Features

- Allows to select Level of Difficulty
  - Easy : Select Random Cell
  - Medium : Checks if next Move can make Computer wins then select it, or next Move can make Player wins then block it, otherwise random cell
  - Hard : Same as the Medium, but it will try to fill the middle cell first, so make it nearly impossible to win
- Allow to select First Turn - Either Player or Computer
- Allows to select Own Symbol to Play - Either Cross or Circle
- Game Keeps record of all Wins, Loss, Rounds with list of Records
- Interactive UI

### Implementation Details

- There is a GridMaker class, which is responsible to make Grid for the game, currently we are asked to make 3x3 grid, but it can make grid of any Size
- There is a ShapeMaker class, which is responsible for making Shapes like Circle, Cross , Line etc in the Game
- There is a Settings Struct which has some details values and can be modified including Level, Opponent Type, FirstTurn, MySymbol Etc
- There is a GameLogicManager Class which is made to reduce the cluster of code from the main ViewController, which holds the Game Logic
- There is a RecordManager Class which holds the tableview delegate and datasource methods which shows the old records of Win and Loss

### Features in Pending

- Player vs Player Mode (Can't complete it due to time constraints)
- Allow Player to Change Name

### Short App Demo:

![Short-App-Demo-ticTactoe_in_swift](https://github.com/panchalrajan/ticTactoe_in_swift/blob/main/CustomViewDemo.gif)

### Long App Demo:

![Long-App-Demo-ticTactoe_in_swift](https://github.com/panchalrajan/ticTactoe_in_swift/blob/main/CustomViewsDemoFull.gif)
