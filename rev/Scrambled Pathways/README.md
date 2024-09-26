# rev - Scrambled Pathways

![Challenge](https://github.com/x03ee/PointerOverflow-Writeups/blob/main/web/The%20Way%20Out%20is%20Through/challenge.png)

### Solution:

1. **Divides the String:** It separates the original string into three parts based on their positions (every third character).

2. **Fills Three Bins:**
   - The first bin collects characters from positions 0, 3, 6, etc.
   - The second bin collects characters from positions 1, 4, 7, etc.
   - The third bin collects characters from positions 2, 5, 8, etc.

3. **Recombines the Characters:** It combines the characters from the three bins in a specific order to create a new string.

4. **Prints the Result:** Finally, it prints the newly formed string as the "Flag". 

   
![Solution](https://github.com/x03ee/PointerOverflow-Writeups/blob/main/web/The%20Way%20Out%20is%20Through/flag.png)

### Final Flag:
```
H7CTF{8485c79f20fa97227b92a476714c8081}
```
