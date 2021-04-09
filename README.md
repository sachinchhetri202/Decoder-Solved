# Decoder-Solved
CS1400 Assignment Solved
The file encryption technique that was used to encrypt the file is a Caesar cipher.  
A Caesar Cipher works by shifting all the letters in the file by a certain amount. 
So for a file with an encryption key of 1 an “a” will be represented by a “b”, and a “b” will be represented by a “c” in the encrypted file.  
With an encryption key of 2, an “a” will be represented by a “c”, and a “b” will be represented by a “d” in the encrypted file.  
This means to decrypt the file, you will need to subtract that amount from the file.  Prompt the user for the file name, and for the encryption key. 
Output the file to a new file named “Decrypted.txt”.  Then open the Decrypted file to make sure the files look like the English language.  

HINT: A char is a character from the ASCII Table. 
Because the ASCII Table is just an ordered set of characters, we can use the ++ or -- to move forward and backward in the ASCII 
Table just like we do to increment or decrement an integer.  Look at the example below, it changes the letter 'A' into a 'B' by adding 1 to the letter.

