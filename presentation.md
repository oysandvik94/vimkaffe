# Vimkaffe

	+--------------------------------+
	|#                               |
	|~                               |
	|~                               |
	|~                               |
	|~                               |
	|"file.txt" [New]                |
	+--------------------------------+

---

# Vimkaffe

- Hvorfor bryr vi oss om Vim i 2024?

///Vim er bygd på software fra 70 tallet, vi har IDE og vscode

***

## Arkansk og foreldet?

/// Ta opp myter og memes

- How do you exit vim?
- Bare brukt til å config fil på server?

---

# Vimkaffe

*"Most loved editor"*

Brukt av flere profilerte kodere

Rikt plugin system med language support

Kan debugge, HTTP klient, DB klient

---

# Hvorfor vim?

- Smidig, uten bloat
***
- I terminalen
***
- Tastatur-sentrert
***
- Putter deg nærmere juicen
***
    - Abstraksjoner skal spare tid, ikke skjule kunnskap
/// IDE abstraherer mye bort om hvordan programvare fungerer
/// Hvis man lærer seg det som er bak abstraheringen er man bedre utstyrt for debugging etc


--- 

# De 2 viktigste tingene

---

# Hvorfor vim?

**Man kan lage sitt eget arbeidsmiljø**

Tilpass editoren din etter deg, og ikke motsatt

## IDE -> PDE

*Personalized Development Environment*
---
 
# Hvorfor vim?

**Man kan kode mye raskere**

> Edit Text at the Speed of Thought 
> -- Drew Neil

/// Man bruker ikke mesteparten av tiden på faktisk kode
/// Men det er verdi å prototype kode raskt
/// Man opplever koden mer, og kan gå fortere igjennom utkast
/// 80 wpm


---

# Hva er Vim?

---

# Vim er en modal editor

Vim har flere moduser som styrer hva knapper gjør
/// Derfor skjer det rare ting når man åpner vim og skriver

--- 
Mesteparten av tiden *editerer* vi kode

***

- Normal mode
***
- Insert mode
***
- Visual mode
***
- Command mode
***
- etc etc

---

# Vim motions

Vim har et "språk" for å utrykke endringer

***

## Man beveger pilen med tastaturet

- hjkl
***
- w,b,e
***
- Kan kombineres med tall
***
- $,_,%
***
- f,t!!
***

## Insert mode

- i,a I,A o,O

## Normal mode

- d,c
***
- inside x

---

# Magiske ting

- ctrl-a, ctrl-x
***
- gU
***
- .
***
- macro
***
- !

---

# Vimkaffe

La oss ta den blå pillen

⢕⢕⢕⢑⠁⢁⣼⣿⣻⢿⣟⢿⡻⡙⡏⡏⣟⡽⡹⣹⢪⡻⢽⡫⠯⣻⢛⢿⣻⣿⣿⡿⣧⢍⠝⡍⡏⡎⡕⢵
⢕⢕⠸⡐⣠⣿⣗⢯⡺⡽⡸⡅⠕⢕⢐⠑⢕⠸⢙⢕⢱⢸⠸⢜⠴⡈⡜⡔⢅⢟⢞⣿⣿⣧⠨⡊⣜⢜⢜⡵
⢕⢌⢂⢀⣿⡷⡧⣯⡣⡹⡎⠪⣈⡂⣦⣁⣱⡱⣱⣡⢑⣘⡨⢮⢝⢞⣎⣖⣵⢳⣸⣯⣿⣿⣇⢣⢪⡪⣣⣻
⢕⢐⠄⣸⣿⣿⡝⣮⡪⡪⣊⢎⡔⣗⢳⢪⢻⠾⡻⡿⡻⣗⢾⢗⡿⢿⢻⡻⡾⣟⣶⣯⣿⣿⡇⡎⢆⢇⢇⢿
⢕⠐⠄⣿⣿⣿⡽⢜⡲⣇⣷⡛⢗⢙⠹⠘⠔⠑⠉⠘⠜⠑⠔⠑⢘⠈⠂⠊⠘⠈⠈⠘⠹⢿⡧⡣⡣⡣⡳⡽
⢅⠅⠄⣿⣿⣿⢝⢷⣻⡻⠁⠄⠄⠄⠄⢀⠄⠄⠄⠄⠂⠬⡀⡄⠄⠄⠄⡀⠄⠄⠄⠄⠁⠂⢻⣕⢧⢳⢕⣿
⠅⠂⠄⢻⣿⣯⠧⢟⣿⣔⠄⠁⡀⡀⠄⠄⠄⣀⠄⠄⡀⠩⠳⠵⠁⠄⡀⠄⢰⣁⠄⠠⠄⠄⠈⢿⣪⡺⡜⣾
⢵⣷⠶⣼⠏⣿⠹⡙⠄⠁⠄⠖⠂⠄⡀⠄⠄⠹⣾⠄⠄⢔⣻⣿⡳⠄⠄⠄⠈⡷⠠⠄⠄⠄⠄⣼⡟⠵⡭⣻
⡪⡂⡕⡄⢠⣿⣏⢌⢠⠰⡌⡢⠄⠄⠅⠠⠄⠐⠄⠄⡔⣵⢾⣟⣯⢧⢂⢠⢀⠄⠄⠄⣀⢤⢾⢦⣿⣇⢗⣿
⠜⣔⠄⠈⢘⣿⣯⡖⠔⠑⢜⢐⠁⢂⠄⠢⢐⠐⢀⢕⢝⡚⡟⠿⡿⣿⣪⡢⠳⣭⣊⢆⠣⠣⠣⠓⡯⢷⡣⣿
⠝⣾⠄⠄⢸⣹⣷⣆⢀⢑⢐⠰⢈⢐⠨⠨⠠⠐⡎⠫⠑⢌⠌⡈⡈⠪⠚⠷⠈⠰⢕⢟⢎⢎⠂⠌⣾⣿⢸⣺
⢅⠱⢷⢄⡀⢽⣿⣟⡀⠑⡐⢅⢃⠢⠑⠅⢅⢢⠈⠄⠄⠄⠁⠐⠈⢀⢀⢬⢤⢠⢌⠪⠲⢈⠸⡠⣿⢾⠱⣽
⡅⠄⠳⣝⠄⢸⣿⣻⡜⠆⠌⣐⡂⢅⠅⡍⡆⢧⢑⢦⠕⠔⠤⠤⠤⠳⢯⣯⢿⢵⠥⡧⣑⢄⠃⣆⣿⠃⢑⢵
⢆⠕⡠⡉⠃⠸⣿⣿⡸⠰⢁⢐⠄⡥⡪⠢⡸⡸⢊⠁⠄⠡⠡⠨⠐⠄⠈⠈⠫⡇⠟⣜⣖⡔⠥⣢⣻⠄⠄⡸
⡣⡣⡱⡨⠢⡀⢹⡗⡳⡉⢐⠄⠕⡽⢐⠁⠄⠅⠐⠈⠄⠄⠄⢀⢀⣀⣀⣀⠄⠁⠄⠨⣾⣗⡘⣆⣿⠄⠐⡌
⡪⡪⡢⡣⡃⢆⠸⣿⡢⡸⠂⡘⡩⠼⡄⢄⠰⡐⢔⠑⢍⢚⢙⢊⠣⠓⠝⢚⢹⢕⢕⢡⠺⡒⠕⠅⡾⣤⣐⢜
⡕⢕⢸⢨⢊⠆⡂⡹⣯⣪⡀⡄⢜⡽⡀⢢⠊⡊⡢⢑⢀⠄⡀⠄⠄⡀⠄⡊⠮⡪⡊⢆⢆⠯⢨⢢⠁⠄⣿⣽
⢎⢕⢕⢅⢇⣣⡱⠒⢿⡜⣖⡂⢚⡺⣎⢐⠄⡊⡐⠰⡀⡅⣀⡢⣐⢔⡰⡨⡘⡄⡣⡡⣏⡓⠇⠁⠄⠄⣍⣿
⡣⡱⡡⡣⣳⠞⠄⠄⠸⣿⣝⢮⣶⢪⡗⡄⠠⢂⠌⠆⡅⠇⠇⡓⡘⡘⡪⣚⠪⡪⡘⡜⡂⢪⡃⠄⠄⢀⣽⢿
⡕⢕⢕⢽⠁⠄⠄⠄⠄⡑⠌⠹⢹⢹⢭⢻⡅⡆⡈⡠⠠⠁⡂⠄⠄⠠⢀⠂⠅⡃⠅⠁⡄⡣⡂⠄⢠⢙⢄⢾
⡕⡕⢵⠃⠄⢀⠄⠡⠄⢈⢂⢀⠄⠁⠌⠈⠪⠒⠢⠐⡐⠡⠐⠠⠡⠈⠄⠌⠄⠄⢀⠌⡀⠊⢐⡴⠩⡓⠔⢝
⢎⢪⢸⠄⠄⠘⠐⠄⠄⠄⠐⡀⠌⡀⠄⢂⠠⠄⠄⠁⠄⠁⠄⠄⠄⠄⠄⠄⠄⠄⡀⠄⡠⠔⠁⠐⠐⡭⡨⡘
⢕⠅⢝⣕⠄⠄⠄⠄⠄⠄⠄⠐⠄⠄⠄⠠⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⡀⠅⠐⠁⠄⠄⠈⢀⠁⡒⡊⠌
⡕⣌⣄⣿⣾⣄⠄⠄⠄⠄⠄⠄⠂⠁⠄⠄⠄⠄⠄⠄⠄⠄⠄⢀⠄⠄⠈⠄⠄⠄⠄⠄⠄⠈⠄⠄⠄⢂⠠⠠

---

# Vimkaffe

- Vimtutor
- Vim mode i editoren din
