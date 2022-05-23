# The C Programming Language Open Source Anki Deck
Welcome!
This is an attempt to make a definitive flashcard version of the book: The C Programming Language
The tips for contributing to this project:
  - try to make the cards as simple as possible so that it is easy to remember e.g. by using cloze cards or by using the Immage Occlusion addon
  - Cards should be made in their approiate deck. e.g. a flashcard with keywords as theme could be placed in Appendix A - Reference Manual Deck -> 02 Lexical Tokens Deck-> 04 Keywords Deck
  - Have fun learning the cards and contributing to the knowledge of others
  - More TBA
  
##### Add-on [CrowdAnki](https://desktop.github.com/)
  - Check his project page to find the CUI intructions
 
### CLI workflow
#### Initiating collaboration
4. Install git on your computer.
5. Go to the directory that resulted from export.
6. Initialize repository with following commands:
   
    ```
    git init
    git remote add origin git@github.com:<username>/<repository>.git
    ```

    Where <username> is your GitHub username (in my case Stvad) and <repository> is the name of the repository (DeckX). So in our case the command will look like:

    ```
    git remote add origin git@github.com:Stvad/DeckX.git
    ```
7. Add the content of your directory to the repository:

    ```
    git add *
    git commit -m "initial export"
    ```
8. Upload changes you've made to the GitHub:

    ```
    git push origin master
    ```

#### To start working on the deck you need to:

1. Install git on your machine.
2. Clone the repository:

    ```
    git clone git@github.com:saladuit/The-C-Programming-Language-Flahscards.git
    ```

3. [Import the deck](#import).

If you **just wants to use the deck** you can [import decks directly from there](#import-from-git).

#### How to upload changes

When you want to upload changes you've made to the GitHub, you need to:

1. Get the latest changes from the GitHub:
   
    ```
    git pull
    ```
2. [Import the deck](#import) to combine changes you've made the project.
3. Export the deck the same directory where your repository is located so that export will overwrite media directory and JSON file in the repository. (As an alternative you can export it elsewhere and copy JSON file and media directory yourself to overwrite the ones that are in repository directory.)
4. Add the changes to the repository:

    ```
    git add *
    git commit -m "new updates"
    ```
5. Upload changes you've made to the GitHub:

    ```
    git push origin master
    ```

If you just want to **get latest changes** - you need to perform only steps 1 and 2.

