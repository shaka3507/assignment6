## Shaka Wordle

## Live URL
https://shaka3507.github.io/assignment6/index.html

### API used
I used [free dictionary api](https://dictionaryapi.dev/) because the response was easy to parse - if the word is found in the dictionary it returned a 200 status. If the word was not found, it returned a 404 (not found). The code is open sourced so you can see exactly how the words included [github link](https://github.com/meetDeveloper/freeDictionaryAPI/blob/master/meta/wordList/english.txt). If I ever wanted to make my own word list, I could fork this repository, update the english.txt list host my own API. 

### Satisfying piece of the assignment
The most satisfying piece of this assignment was redesigning the UI. The Wordle user interface is iconic and often replicated. Finding a balance to make it more minimal, and convey enough information was challenging in itself. Also ensuring all the pieces of the UI updated when a person wanted to play again was challenging, essentially trying to reset the state of the game. 

### Requirements
- [x] display letter indicator that the user can avoid letters that are eliminated
- [x] include optional 'debug' mode - switchable at the start of game (click to see answer)
- [x] allow user to play multiple games
- [x] responsive to tablet size
- [x] comments preceding each function
- [x] works online

### optional reqs
- [x] animation after win
- [x] responsive to 600px wide
