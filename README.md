# Tandem Trivia By Yoel Morad

### How to Install Locally

1. Fork and clone [this](https://github.com/yoel0/Tandem2020) repository.

2. Open the file with your IDE (VScode, Atom, Sublime etc) of choice.

3. Open the index.html in your browser with ```open index.html``` cmd in your terminal or open with liveserver extention can be found [here](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

4. Have fun playing!
---
## User Stories

> A user can view questions.

> A user can view questions with multiple choice options displayed one at a time. 

> A user can select only 1 answer out of the 4 possible answers.

> A user can see the score they received at the end of the round and after each question +10pts per question answered correctly.

> A user can save their High Score at the end of a round as well as their user name of choice.

---

## Options for Trivia
1. if desired to use Tandems local questions, one may navigate to game.js and uncomment out lines 19-30.
```javascript 
//--Uncomment to Load Local Tandem Questions/JSON--//
// fetch('questions.json')
//   .then((res) => {
//     return res.json();
//   })
//   .then((loadedQuestions) => {
//     questions = loadedQuestions;
//     startGame();
//   })
//   .catch((err) => {
//     console.error(err);
//   });
```
- Otherwise by default trivia will be played with fetched API from TrviaDB on computer science which can be found [here](https://opentdb.com/)

Happy Trivia!