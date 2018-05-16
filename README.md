# puntender
Joke understanding using WordNet and ConceptNet, on the joke structure, "____ walks into a bar. The barman says, '_____'".

There are two main programs: one which does analysis via WordNet (wordnetmain.py) and one which does analysis via ConceptNet (conceptnetmain.py). Both of these run using python3. If you do not have python3 installed, you can follow the installation instructions at the bottom.

Before running the programs, you should run the following commands in the terminal to install the necessary modules and download the needed nltk packages. 
```bash
python3 setup.py
```
To run the WordNet analyzer, run
```bash
python3 wordnetmain.py
```
To run the ConceptNet analyzer, run
```bash
python3 conceptnetmain.py
```

# Installing python3
This tutorial assumes you are using a Mac. The simplest way to install python3 is using Homebrew. You can check if you have Homebrew installed with the following command.
```bash
brew --version
```
If so, then you can run the following to install python3:
```bash
brew install python3
```
Otherwise, if you don't have Homebrew installed, you can first run the following:
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
