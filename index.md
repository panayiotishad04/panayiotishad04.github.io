# c4ptur3-th3-fl4g
## Translation & Shifting
### c4n y0u c4p7u23 7h3 f149?
Here we simply try to much each number with a suitable character. For example, 4 -> a and 7 -> t.
By doing this for all letter we get: can you capture the flag?

### 01101100 01100101 01110100 01110011 00100000 01110100 01110010 01111001 00100000 01110011 01101111 01101101 01100101 00100000 01100010 01101001 01101110 01100001 01110010 01111001 00100000 01101111 01110101 01110100 00100001
Here we see a pattern of 8 bits in a row space and again 8 bits. This looks like characters represented in binray. One character has a length of 1 byte, which is 8 bits. If we put this into a translator we get the following answer: lets try some binary out!

### MJQXGZJTGIQGS4ZAON2XAZLSEBRW63LNN5XCA2LOEBBVIRRHOM======
Seeing the = signs in the end signaled for base encoding, which was base 32

### RWFjaCBCYXNlNjQgZGlnaXQgcmVwcmVzZW50cyBleGFjdGx5IDYgYml0cyBvZiBkYXRhLg==
With the same idea here we see a padding of only 2 which is the maximum for base64. By putting this string into a decode we got: Each Base64 digit represents exactly 6 bits of data.

### 68 65 78 61 64 65 63 69 6d 61 6c 20 6f 72 20 62 61 73 65 31 36 3f
We observer pairs of letters and number, where the letter goes until f. This means the flag is represented in hexadecimal. Decoding it we get: hexadecimal or base16?

### Ebgngr zr 13 cynprf!
This look like this characters were shifted by a certain amount of times, which was in fact 13 when we put into a cipher text decoder. We obtained the following flag: Rotate me 13 places!

### *@F DA:? >6 C:89E C@F?5 323J C:89E C@F?5 Wcf E:>6DX
This again looked liked it has been rotated, however we observer that it included also symbles. 47-ROT is a variation of cipher which includes 47 characters. The decoder gave us this: You spin me right round baby right round (47 times)

### 