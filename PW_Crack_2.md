## PicoCTF Challenge: PW_Crack_2

## Goal:
Find password that runs script to decrypt flag. 

## Steps I Took:
1. Used "wget" to retrive files.
2. Opened python script in VSCode.
3. identified password to unlock script was chr(0x64) + chr(0x65) + chr(0x37) + chr(0x36).
4. Printed result in different file, retrieved password, and ran python script in shell on encrypted flag

## Output:
picoCTF{tr45h_51ng1ng_489dea9a}

## Takeaway:
This challenge reinforced the importance of understanding how scripts obfuscate data and how to reverse that process. By breaking down the chr() calls into their ASCII equivalents, I saw how a password could be hidden in plain sight.
