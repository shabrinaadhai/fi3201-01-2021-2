# Assignment 03
# Question 1 : Ganti nilai variabel NIM dan jalankan kode
```
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')
```
```
NIM = '10219070'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```
# answer 1
```
Traceback (most recent call last):
  File "HelloWorld.py", line 10, in <module>
    s += char
NameError: name 'char' is not defined
```
# question 2 : modifikasi kode dengan s += char1 dan jalankan hasil nya
```
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')
```
```
NIM = '10219070'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char1
  print(n, ':', s, sep='')
```
# Answer 2
```
1:◻
0:
2:◻◻
1:◻
9:◻◻◻◻◻◻◻◻◻
0:
7:◻◻◻◻◻◻◻
0:
```
# question 3 : modifikasi kode dengan s += char2 dan jalankan hasil nya
```
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')
```
```
NIM = '10219070'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char2
  print(n, ':', s, sep='')
```
# answer 3 
```
1:◼
0:
2:◼◼
1:◼
9:◼◼◼◼◼◼◼◼◼
0:
7:◼◼◼◼◼◼◼
0:
```
# question 4 : Jelaskan kode tersebut
# answer 4 
```
1. kode diatas berfungsi untuk Menghitung string baru di mana urutan escape diganti dengan karakter yang diwakilinya atau dalam kata lain unescape() menggantikan nama entitas atau nomor entitas dari suatu karakter HTML yang dicadangkan dengan representasi karakter aslinya. 
2. Karakter pada char1 (&#x25FB;) dan pada char2 (&#x25FC;) merupakan kode nomor unicode dengan entitas html yang menghasilkan simbol kotak tidak di bold pada kode char1 dan tidak di bold pada kode char2
```
