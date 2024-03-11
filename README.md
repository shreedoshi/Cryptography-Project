# Cryptography-Project
Uses cyrptography methods to encrypt and decrypt messages.

Cryptography has played a crucial role in securing sensitive information in the past and continues to do so in today's digital world. In this project, I have attempted to implement three ciphers namely
- Ceaser Shift Cipher
- A substitution cipher - Morse Code
- Vigenere Cipher


## Below are brief description of each cipher:

### 1)CAESER SHIFT CIPHER
Caeser Shift Cipher is one of the simplest and oldest encryption techniques. It is a type of substitution cipher, where each letter in the plaintext is replaced by another letter that is a fixed number of positions away in the alphabet. The number of positions is the key of the cipher.
Example: For an encryption with a key 3,
     the first letter, 'A' in encryption would be 'D' 
     Similarly, 'B' in encryption would be 'E'
                'C' would be 'F' and so on. 

                
### 2) MORSE CODE- Sustitution cipher
Morse code is a method used in telecommunication to encode text characters as standardized sequences of two different signal durations, called dots and dashes

Example: 'SOS' in morse code would be '...---...'


### 3) VIGENERE CIPHER- Polyalphabetic cipher
- The Vigenère cipher is a method of encrypting alphabetic text using a simple form of polyalphabetic substitution. It was invented by Blaise de Vigenère in the 16th century and was considered unbreakable for centuries. The Vigenère cipher is more secure than a simple Caesar cipher, which is a monoalphabetic substitution cipher.

- The Vigenère cipher is a method of encrypting alphabetic text where each letter of the plaintext is encoded with a different Caesar shift cipher, whose increment is determined by the corresponding letter of another text, the key.

- to encode the message using vigenere cipher, the algorithm is as follows: formula: enciphered index = (plaintext index + keyword index) mod 26

- to decode the message using vigenere cipher, the algorithm is as follows: formula: deciphered index = (enciphered index - keyword index) mod 26

- For example, To encrypt 'ATTACK AT DAWN' with the keyword 'LEMON'

         Plaintext:     ATTACKATDAWN
         Key:           LEMONLEMONLE
         Ciphertext:    LXFOPVEFRNHR
- the first letter of the plaintext, A, is paired with L, the first letter of the key and encrypted. Similarly, for the second letter of the plaintext, the second letter of the key is used. The rest of the plaintext is enciphered in the same way by repeating the key.

### About the project:

- This project allows the user to pick a method of cryptography and encrypt or decrypt their message.
- The menu first asks the user to choose a method and if they want to encode or decode their message.
- It then asks them to input a message and a key if needed to encode/decode the message.
- Below is the code for the project.

  
