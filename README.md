# Advance-Dictionary
Our project is a word dictionary which has been developed using the c++ programming language. It can perform a variety of functions such as inserting new words into the dictionary, deleting words, looking for a specific word, printing all of the dictionary’s words in alphabetical order, finding synonyms for a word and finally the most distinct of all, a prefix search where if you enter only the initials of a word, the program displays all the related words which you could be searching for and those starting with the given initials.

## Data Structure Time Complexity:
Using Trie, search complexities can be brought to optimal limit (key length). If we store keys in binary search tree, a well-balanced BST will need time proportional to M * log N, where M is maximum string length and N is number of keys in tree. However, the penalty is on Trie storage requirements. Insert and search costs O(key-length), however the memory requirements of Trie is O(ALPHABET_SIZE * key-length * N) where N is number of keys in Trie. 
Trie supports search, insert and delete operations in O(M) time where M is length of key.
