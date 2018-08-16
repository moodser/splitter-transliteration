# splitter for generating transliteration corpus
## Description
- This is Python script that uses the text file generated by 'Wikipedia Parallel Title Extractor - https://github.com/clab/wikipedia-parallel-titles' as an input.
- This script process the input text file (mentioned above) to generate a parallel corpus. 
- Output of this script (parallel corpus) can be used to train transliteration model on MOSES.
## Author
Moodser Hussain
- COMSATS University Islamabad, Lahore Campus
- Email: moodser.hussain@gmail.com
## Acknowledgement
Special thanks to Dr. Rao Muhammad Adeel Nawab and Sir Muhammad Sharjeel for their continous support.

## Usage
- Download the script file (splitter.py)
- Copy the input file (generated by wikipedia parallel title script) in same directory
- run the terminal/cmd command 'python splitter.py <name-of-input-file>'
- Two output files will be generated for each language seperately.

## Caution
- This Script is tested on English-Urdu parallel titles extracted from https://dumps.wikimedia.org/urwiki/20180801/ using https://github.com/clab/wikipedia-parallel-titles
- Python version 3.6 was used for testing this script.
