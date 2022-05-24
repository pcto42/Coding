
# PCTO

## ex00

Il programma prende due numeri e controllare se il primo è maggiore del secondo.

## ex01

L'utente inserisce la propria età e il programma dice se è maggiorenne (ovvero con età maggiore uguale a 18 anni).

## ex02

Il programma legge due numeri e controlla se il primo è multiplo del secondo.

## ex03

L'utente inserisce una temperatura in Celsius. Se la temperatura inserita è minore dello zero assoluto (-273,15 ºC), il programma segnala un errore. Atrimenti il programma converte la tempreratura in Fahrenheit ed in Kelvin e stampa i valori.

> Ricorda che:
>
> Fahrenheit = (9/5) · Celsius + 32
>
> Kelvin = Celsius + 273,15

## ex04

Il programma letti tre numeri, determini se possono essere considerati in progressione aritmetica; una progressione aritmetica è una serie di numeri in cui la differenza tra due numeri successivi è costante.

## ex05

L'utente inserisce un anno ed il programma verifica se l'anno inserito è bisestile.

Un anno è bisestile se è divisibile per 4 ma non per 100, oppure se è divisibile per 400.

|      |               |
| ---- | ------------- |
| 1900 | non bisestile |
| 2001 | non bisestile |
| 2000 | bisestile     |
| 2004 | bisestile     |

## ex06

Il programma legge tre numeri e dice se possono essere le lunghezze dei lati di un triangolo (perché un triangolo possa essere tale la somma di ogni coppia lati deve essere maggiore dell'altro).

## ex07

Il programma legge tre lunghezze dei lati di un triangolo e dice se il triangolo è scaleno, isoscele o equilatero.

## ex08

La prima volta che l'uomo è andato sulla Luna è stato il 1969, creare un programma che chiede l'anno di nascita all'utente e gli risponde se è nato l'anno in cui l'uomo è andato sulla Luna o quanti anni prima o quanti anni dopo.

## ex09

Il programma stampa tutti i numeri tra 20 e 50 compresi.

## ex10

Il programma stampa i numeri pari compresi tra 0 e 100 in ordine decrescente.

## ex11

Calcolare la somma dei numeri pari compresi fra 2 e 100. Il problema consiste nel sommare 2 + 4 + 6 + 8 … + 100.

## ex12

Crea un programma che stampa tutti i numeri da 1 a 100:
-Qualora il numero fosse divisibile per 3, il programma stampa fizz al posto del numero;
-Qualora il numero fosse divisibile per 5, il programma stampa buzz al posto del numero;
-Qualora il numero fosse dibisibile sia per 3 che per 5, il programma stampa fizzbuzz al posto del numero.
```
1
2
fizz
4
buzz
fizz
7
8
fizz
...
13
14
fizzbuzz
...
```

## ex13

L'utente inserisce due numeri interi (base e esponente). Se l'esponente è positivo, il programma stampa la potenza. Altrimenti stampa errore.

## ex14

L'utente inserisce un numero intero e il programma ne stampa il fattoriale.

## calculator

Crea un programma che una volta avviato riceverà in input un numero, seguito da un segno (+, -, /, *, %) e da un ultimo numero. Una volta inseriti i dati il programma restituirà in output il risultato del calcolo. Fai attenzione a controllare che le operazioni ricevute siano valide.

Esempio:

```
5 + 5
10
```
```
10 * 5
50
```
```
7 / 0
ERRORE
```
```
10 y 7
ERRORE
```

## bonus00

L'utente inserisce un numero, maggiore o uguale a 2, e il programma stampa a schermo se il numero inserito è primo o meno. Se il numero è minore di 2, il programma stampa un messaggio di scherno nei confronti dell'utente.

## bonus01
Il programma prende una sequenza di lunghezza ignota a priori di numeri interi positivi. Il programma, a partire dal primo numero introdotto, stampa ogni volta la media di tutti i numeri introdotti. Terminare quando il numero inserito è negativo.

## bonus02

Stampa a schermo tutte le possibili coppie di due cifre (0-9), **senza ripetizioni**.

Esempio:

```
00
01
02
...
09
11
...
```

Nota come nella sequenza venga saltato `10`.

## bonus03

L'utente inserisce un numero intero positivo e il programma stampa il valore della serie di Fibonacci nella posizione del numero inserito dall'utente.

Esempio: L'utente inserisce 8 e il programma stampa 21, l'ottavo numero della sequenza.






## CHAR00

Crea un programma che stampi l'alfabeto (E' obbligatorio utilizzare la tabella ASCII);

## CHAR01

Crea un programma che stampi l'alfabeto al contrario (E' obbligatorio utilizzare la tabella ASCII);

## STRING00

Crea un programma che, una volta inserita una frase la stampa al contrario:
```
Inserisci una frase: Ciao a tutti!!!
!!!ittut a oaiC
```

## STRING01

Crea un programma che prende in input una frase e stampa a schermo la prima parola in quella frase:
```
Inserisci una frase: Ciao a tutti!!!
Ciao
```

## STRING02

Crea un programma che prende due argomenti, il primo è una frase, il secondo è un carattere. Il programma conterà la ricorrenza del carattere inserito all'interno della frase inserita.

```
Inserisci una frase: Benvenuto al PCTO Coding & Problem Solving
Inserisci una lettera: e
La lettera e appare 3 volte
```
```
Inserisci una frase: Che noia il coding
Inserisci una lettera: C
La lettera C appare 1 volte
```
