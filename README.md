# Catch'em All 2: The grep Edition

In the forest, our scanners have detected the presence of pokemon.

### Part 1: Catch 'em
- **a)** In the answers file, found in the greps directory, show the grep statement you used to catch each pokemon and save to a txt file, in the format `[pokemon name].txt`

grep -E "beed" filescan_00.1 > ../captured/beedrill.txt

grep -E "blas" filescan_00.1 > ../captured/blastoise.txt

grep -E "butt" filescan_00.1 > ../captured/butterfree.txt

grep -E "bulb" filescan_00.1 > ../captured/bulbasaur.txt

ggrep -P "mander" filescan_00.2 > ../captured/charmander.txt

ggrep -P "izard" filescan_00.2 > ../captured/charizard.txt

ggrep -P "meleon" filescan_00.2 > ../captured/charmeleon.txt

ggrep -P "ivy" filescan_00.3 > ../captured/ivysaur.txt

ggrep -P "jigg" filescan_00.3 > ../captured/jigglypuff.txt

ggrep -P "pika" filescan_00.3 > ../captured/pikachu.txt

ggrep -P "meow" filescan_00.3 > ../captured/meowth.txt

ggrep -P "psyd" filescan_00.4 > ../captured/psyduck.txt

ggrep -P "squi" filescan_00.4 > ../captured/squirtle.txt

ggrep -P "wart" filescan_00.4 > ../captured/wartortle.txt

ggrep -P "venu" filescan_00.4 > ../captured/venusaur.txt

- **b)** 
Save the each pokemon as a separate `.txt` file in the `captured` directory.


- **c)** In which section of the forest (which scan file) did you find each pokemon?


### Part 2: Stats
- **a)** How many pokemon are there? Show your grep that you used to get to that number.
wc *


- **b)** Who are the three biggest pokemon? (number of lines)
Show the grep that you used to get to the result.
wc *

318 charizard
300 venusaur
270 wartortle

(Hint: remember to use `ggrep -P "(whatever your pattern is)" [whatever your file is]`)



