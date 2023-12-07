

<div align="center">
 

  <h3 align="center">BASH RPN Calculator</h3>

  <p align="center">
School project for my BSc
    <br />
    <br />
:D
  </p>
</div>



## About The Project


This project comes from my bash courses in my BSc. 

### Built With

Raw BASH

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.


Start the program
  ```bash
bash rpn.sh
  ```
or
```bash
./rpn.sh
```

Make sure the program is executable

### Installation

You just need to install **bc** and **figlet**

```bash
sudo apt install bc figlet
```



## Usage

The program run without arguments. Therefore, you can add -h to the program in order to see how to use it.

Here is a sample of the usage. As you can see, it handles float and negative number


```bash
┌──(kali㉿kali)-[~/ESSIR/RPN]
└─$ bash rpn.sh
  ____ ___ _____   _   _ ____  _____ ____    __   
 / ___|_ _|_   _| | | | / ___|| ____|  _ \   \ \  
| |  _ | |  | |   | | | \___ \|  _| | |_) | (_) | 
| |_| || |  | |   | |_| |___) | |___|  _ <   _| | 
 \____|___| |_|    \___/|____/|_____|_| \_\ (_) | 
                                             /_/  
[+] >>> 45
[+] >>> 74
[+] >>> add
[+] >>> dump
119
[+] >>> 6
[+] >>> %
[+] >>> dump
.00000000000000000002
[+] >>> clear
[+] >>> dump
[+] >>> 23.534
[+] >>> 765.8
[+] >>> *
[+] >>> dump
18022.3372
[+] >>> 3
[+] >>> *
[+] >>> dump
54067.0116
[+] >>> 5
[+] >>> /
[+] >>> dump                                                                     
10813.40232000000000000000
[+] >>> 6
[+] >>> dump
10813.40232000000000000000
6
[+] >>> swap
[+] >>> dump
6
10813.40232000000000000000
[+] >>> dup
[+] >>> dump
6
10813.40232000000000000000
10813.40232000000000000000
[+] >>> 425.542
[+] >>> -3729
[+] >>> 5.22
[+] >>> -3809.42
[+] >>> sum
[+] >>> dump
-7107.658



```


#### Features :

**Add** | **+** : Add the n-2 to the n-1. 

**Substract** | **sub** | **-** : Substract the n-1 to the n-2

**Multiply** | mul | **`*`** : Multiply the n-2 by the n-1.

**Division** | **div** | **/** : Divide the n-2 digit by the n-1.

**Modulo** | **m** | **%** : Modulo operation.

**Power** | **^** | **``**``** : Power operation.

**Quit** | **exit** | **q** : Quit the program.

**sum** | **somme** : Add all the numbers in the stack.

**dump** | **d** | **stack** : Print the stack in the terminal.

**swap** : Swap the last numbers entered.

**clear** | **drop** : Clear the stack, reset to 0.

**dup** : Duplicate the last number entered.


Arrow up and Arrow down are handled :)


## Notes 

```bash
-11962.26
[+] >>> dup
[+] >>> power
Runtime warning (func=(main), adr=23): non-zero scale in exponent
```
If the calcul is too big to process, it may print this. 
If you want to compute big equations, you may want to change the language and you computer.


## Contributing

Feel free to contribute. Do what you want with this project :)


## License

Distributed under the MIT License. See `LICENSE.txt` for more information.


## Contact

Autéqia

Project Link: https://github.com/strange-fruit/bashRPN


## Author : 

Nicolas M
