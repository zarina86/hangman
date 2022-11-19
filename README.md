# Hangman
Game for fun, guess the words
## Installation:
Install Ruby by following the instructions [link](https://www.ruby-lang.org/en/documentation/installation/)

Clone repository to your computer

    git clone  

Move to cloned project's directory

    cd hangman
    
Install bundler to your project

    gem install bundler   
    
Install required dependencies

    bundle install    
    
## How to execute:
#### Run the following command:
    bundle exec ruby hangman.rb
#### The game rules:
1. The program asks player to guess the word and shows how many letters it has.
2. Player/gamer has 7 tries to figure out the word.
3. Player types letters one by one.
4. For each letter the player guesses wrong the gallows will be drawn.
5. If player guessed the full word he/she won.
6. If the player guesses a correct letter,the program shows how many times and where this letter appears in the word.
5. If player didn't guess the letter the program counts as a mistake.
