  Provide a utility to search text files.  
  
  The tool should have at least two functions: one to initialize the tool with an arbitrary text file, and another to provide search results of the text file for a given search term. The tool should allow for repeated searches to be made, stopping when the user enters an empty search term. In addition to the search term, the search function also takes an integer to specify the number of surrounding context words, if available, to display in the results. 

  If this value is 1, then 1 preceding word, and 1 following word should be displayed. One result (including context words) should be displayed for each occurrence of the search term in the text file. Do not include punctuation before the first context word or after the last context word. 

  Include punctuation placed after the first context word and before the last context word. 

  NB: Good solutions will be written with careful consideration to minimize the amount of time it takes to perform each search. Although the time to initialize the tool may increase as the size of the text file does, please minimize the time required to perform searches subsequent to the initialization. It's okay to use data structures from your language's standard library.
