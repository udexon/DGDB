# Hydegraph &mdash; Decentralized Graph Database using Hybrid API

- Free software revolution 1.0: Decentralization of Code
- Free software revolution 1.5: Blockchain and Cryptocurrencies
- Free software revolution 2.0: Decentralization of Data

Scifi fans may recognize Hyde as one Mr Hyde &mdash; the distant ancestor of Dr. Bruce Banner & the Incredible Hulk. "Hy" is taken from "Hybird API", "de" from "decentralized" and "graph" from graph database. The Hulk analogy is meant to imply that Hydegraph will transform the seemingly powerless user's desktop computers and mobile devices into something that can rival MAGA+F (Microsoft Apple Google Amazon Facebook).


There are at least 3 fundamental paradigm shifts that are required to make this happen -- graph database, decentralized user authentication, hybrid programming language API -- which may explain why it has not been achieved so far, as the likelihood of finding someone or a group of programmers mastering all 3 fields would be infinitesimal.



## I: Graph Database

- A json file is part of a graph database.

This is the first paradigm shift and practical understanding that we wish to impart in order to convince programmers they can contribute to something bigger than MAGA+F.
Academics would not be interested in this debate. 



What only MAGA+F can do in-house, all programmers can do now, producing MAGA+F clones, and better.

Chances of success of similar projects? How did their teams grow?

 
## II: Decentralized User Authentication
The term "decentralized" has been "hijacked and abused" by blockchain advocates in the past few years with some notable, but limited, progress. We adopted this term largely due to the fact that our framework has a common root with blockchain in asymmetric cryptography, and it modifies significantly one of the most fundamental step in network computing: user authentication.


## III: Hybrid Programming Language API

Universal interface script

We have initially demonstrated decentralized user authentication with "Greeting with A Secret Phrase" (GASP) protocol in the following link:

- https://github.com/udexon/XIDT/blob/master/Greet_Secret_Phrase.md

The example above employed Websocket messaging. In applications where SSH tunnel is required, Websocket is problematic. As such, we are implementing GASP over basic AJAX as shown below:

1. The source code for Hydegraph AJAX demo is available here:

- https://github.com/udexon/Hydegraph/tree/master/phos

2. The following commands are entered via the browser console:

```js
c=new JSEncrypt()
F("nxhr: phos.php xo: xsqrh:")
F('a b c s: 9 3 + s: '+ btoa(c.getPublicKey()) 
+' b64d: 4 orpb: hex: dup2: enc: b64e: s:',"je: xsend:")
```

(The HTML web page belong to an older example which briefly describes the principles of Phoscript &mdash; a Forth-like script that can act as a wrapper shell in almost all known programming languages, including Python, JavaScript and PHP.)

i. `c=new JSEncrypt()` initializes a `JSEncrypt` object for asymmetric cryptography.

ii. `F("nxhr: phos.php xo: xsqrh:")` initializes the AJAX connection.

iii. `F('a b c s: 9 3 + s: '+ btoa(c.getPublicKey()) 
+' b64d: 4 orpb: hex: dup2: enc: b64e: s:',"je: xsend:")`

- sends the public key of `c` (`btoa(c.getPublicKey())`) to the back-end
- `b64d:` decodes the public key by calling `base64_decode()` in PHP
- `4 orpb:` generates a 4-byte random number by calling `openssl_random_pseudo_bytes()`
- `hex:` converts the random number into hexadecimal notation (string)
- `dup2:` duplicates 2 items at the top of the stack, so that we may compare the hexadecimal random number in the back-end with the decrypted results in the front-end
- `enc:` encrypts the random number using `openssl_public_encrypt()`
- `b64e:` converts the encrypted message by calling `base64_encode()` so that the results are human readable
- `s:` displays all items on the stack

iv. Finally, the encrypted base64 message is decrypted at the front-end manually using `c.decrypt()`. 

Stack item index [6] `5c4b74da` matches with the result of `c.decrypt()` at the bottom of figure 1.

- Figure 1
<img src="https://github.com/udexon/Hydegraph/blob/master/Hydegraph/GASP.png" width=400>

iv. Obviously, in production mode, we must disable the ability of user to inspect the raw value of the random number generated by the back-end.

The front-end module is supposed to be able to decrypt the encrypted random number generated by the back tend to prove that the user is the legitimate owner of the private key, whose public key was given to the back-end earlier.

3. The link below demonstrates a simple HTTP POST example on updating a JSON file, which can be used as the foundation of a graph database:

- https://github.com/udexon/Multiweb/blob/master/Reddit_anon_comment.md

Together with the decentralized user authentication (DUA) mechanism shown above, we now have the building blocks for Hydegraph:

- decentralized user authentication
- graph database
- hybrid API

4. In the next tutorial, we shall demonstrate using Python Selenium to save the public and private keys generated by JSEncrypt to a local file, as these will be used to identify the user over a period of time.

Further, the user may change his (her) private and public keys _ANYTIME_. The chain of keypairs, together with the period of validity of the keypairs, will be unique enough to identify all human population and devices on Earth in the foreseeable future. As the user has the right to change his (her) keypairs anytime, this is known as Transient Key Cryptography (TKC).

5. From the example above, we show that DUA have fundamentally changed the mechanism of conventional user authentication from being server-centric to user-centric.

As user authentication is one of the most if not the most important mechanism in computer applications, a paradigm shift towards DUA may just create a new segment in the computing industry that may be worth the _EQUIVALENT_ of the industry segment based on server-centric (centralized) user authentication.

6. Get search results in a web spreadsheet, which itself is programmable.


7. It takes a finite time t0 for programmer P0 to convince programmer P1 to believe in this vision, to be called Phosway. Let t_i be the time taken for programmer P_i to convince programmer P_{i+1}. So we hope that t_i < t_{i+1} is true.

When i is small, P_i will be affected by trends in computer programming, more likely to choose to dismiss Phosway rather than believing in it.


<img src="https://github.com/udexon/Hydegraph/blob/master/Hydegraph/equation.svg">

So <img src="https://github.com/udexon/Hydegraph/blob/master/Hydegraph/P_i.svg"> you see.
