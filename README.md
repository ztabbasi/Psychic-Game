# Name of project

Psychic game: Game to test your psychic ability.  The computer picks a letter and the user takes guesses at the letter.
There are 10 attempst allowed.  

# Link to the site

[Psychcic Game](https://ztabbasi.github.io/Psychic-Game/)

# Images

![Picture](assets/images/Untitled.png)


# code snippets

 code below is used to see if the user has guessed correct or not and proceed based on the choices
 
        if(userGuess === computerChoice){
                wins++;
                guesses = 10;
                guessArray = [];
                computerChoice = alphabets[Math.floor(Math.random() * alphabets.length)];
        }else{
             guesses--;
             guessArray.push(userGuess);
             printArray();
        }
        if(guesses === 0){
            losses++;
            guesses = 10;
            guessArray = [];
            computerChoice = alphabets[Math.floor(Math.random() * alphabets.length)];
        }


# Author 
Zia Abbasi

# License
Standard MIT License

