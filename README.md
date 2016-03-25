The MIT License (MIT)
Copyright (c) 2016 Stephan Kristyn (meshfields.de) 
http://meshfields.de/mit-license/

# Console Drawing Tool README
## With this tool you can draw on console in Linux. It uses Python. 

Start: ./main.py
Tests: ./test.py

# Design-Decisions and Trade-Offs

- Decided against nCurses because of requirement to not use a library
- Emphasised on self-explanatory Code and helpful UX/UI

## ToDo's: 

- Re-Write as Class for cleaner testing
- Move DrawBucketFill Test to test.py
- Modularise further

# Libraries

unittest (for TDD)
sys (for basic tools)
regex (for input handling)
