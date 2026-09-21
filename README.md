# Python-3rd-Sem
Contains the experiential learning for Python 3rd semester
# Topic allotted: Word Jumble Game
Develop a Python-based word puzzle game that presents users with with scrambled words. The player must guess the correct word within a limited number of attempts. The application should maintain scores, provide hints, and allow multiple rounds of gameplay.
Theory & Concepts used:
1. Data Structures (Dictionaries and Lists)
Dictionaries(dict): Used as the primary data store for the game's vocabulary. The dictionary maps the target word (key) to its corresponding hint (value). This provides an efficient way to retrieve a hint in time complexity when a user requests one.
Lists(list): Used to handle the characters of a word during the scrambling process. Strings in Python are immutable, so they must be converted to a list of characters before they can be shuffled.

2. Randomization(random module)
random.shuffle(): Applied to lists to randomize the order of elements in place. This is the core mechanic for generating the "jumbled" version of the word.
random.choice() or 
