# BullCowGame
BullCowGame that was created in C++.

Hi Everyone!

This is a simple command prompt game that is played individually. The game only accepts isotopes. This means that the game only accepts words that have no repeating letters. Examples of isotopes: "hop", "jump", "house". Examples of words that are NOT isotopes: "tree", "door", "cook". The game will ask you to enter the number of letters of the word you would like to guess. Once you enter a number, a word will be selected, and you will be asked to guess the "hidden word." The number of tries you have at guessing the word changes depending on the length of the word. If you enter a word that has the same letter as the "hidden word" and it is in the exact same placement as the "hidden word", the bull counter will increase. If you enter a word that has the same letter as the "hidden word" but it is in a different place than the "hidden word" you will get a cow. Examples of a bull: hidden word = "dumb". Your guess is "dock". Bulls = 1 because your guess word has a "d" at the beginning just like the hidden word. Example of a cow: hidden word = "john". Your guess is "horn". Bulls = 2 because of the matching "o" and "n", but Cows = 1 because of the "h" being a correct letter but in the wrong place. The game is relatively short and repetative. Only has up to 8 words, but in the future I plan to find a way to implement changes in the game where the words are selected at random... once I figure out how to do that :). 
