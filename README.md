<scribt>

nextMove(board, true); // this could return [1, 1]
makeMove(board, [1, 1], true);
makeMove(board, [1, 2], false);
{
winner: 'x',
    winningLocations: [[0, 0], [1, 1], [2, 2]] // locations of winning Xs
    }
    {
    winner: 'o',
    winningLocations: [[1, 0], [1, 1], [1, 2]] // locations of winning Os
    }
    {
    winner: 'none' // nobody won, game over
    }
    
    canvas.addEventListener('click', function(evt) {
  // evt.offsetX - x of where the user clicked
  // evt.offsetY - y of where the user clicked
  // Determine which position the user clicked in and call makeMove with that position
}, false);

game.board[0][2] = 'o'; // o move

game.board[1][1] = 'x'; // x move

game.board[2][0] = 'o'; // o move

game.board[2][1] = 'x'; // x move

game.board[1][2] = 'o'; // o move

</scribt>
