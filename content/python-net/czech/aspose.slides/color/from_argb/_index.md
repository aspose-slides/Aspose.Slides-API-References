---
title: from_argb method
second_title: Aspose.Slides pro Python přes .NET API Referenci
description: 
type: docs
url: /cs/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Vytvoří barvu ze 32bitové hodnoty ARGB.

### Vrací

Barva vytvořená ze zadané hodnoty.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| argb | **int** | Hodnota určující 32bitovou hodnotu ARGB (signed nebo unsigned). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **ValueError** | Hodnota komponenty je menší než 0 nebo větší než 255. |
| **TypeError** | Špatný počet nebo typ argumentů. |


## from_argb(alpha, base_color) {#int-color}
Vytvoří barvu ze zadané alfa hodnoty a základní barvy.

### Vrací

Barva vytvořená ze zadaných hodnot.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| alpha | **int** | Hodnota komponenty alfa. Platné hodnoty jsou 0 až 255. |
| base_color | [`Color`](/slides/python-net/cs/aspose.slides/color) | Barva, ze které se vytvoří nová barva. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **ValueError** | Hodnota komponenty je menší než 0 nebo větší než 255. |
| **TypeError** | Špatný počet nebo typ argumentů. |


## from_argb(red, green, blue) {#int-int-int}
Vytvoří neprůhlednou barvu (alfa je 255) ze zadaných hodnot červené, zelené a modré.

### Vrací

Barva vytvořená ze zadaných hodnot.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| red | **int** | Hodnota komponenty červené. Platné hodnoty jsou 0 až 255. |
| green | **int** | Hodnota komponenty zelené. Platné hodnoty jsou 0 až 255. |
| blue | **int** | Hodnota komponenty modré. Platné hodnoty jsou 0 až 255. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **ValueError** | Hodnota komponenty je menší než 0 nebo větší než 255. |
| **TypeError** | Špatný počet nebo typ argumentů. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Vytvoří barvu ze čtyř komponent ARGB (alfa, červená, zelená a modrá).

### Vrací

Barva vytvořená ze zadaných hodnot.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| alpha | **int** | Hodnota komponenty alfa. Platné hodnoty jsou 0 až 255. |
| red | **int** | Hodnota komponenty červené. Platné hodnoty jsou 0 až 255. |
| green | **int** | Hodnota komponenty zelené. Platné hodnoty jsou 0 až 255. |
| blue | **int** | Hodnota komponenty modré. Platné hodnoty jsou 0 až 255. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **ValueError** | Hodnota komponenty je menší než 0 nebo větší než 255. |
| **TypeError** | Špatný počet nebo typ argumentů. |



### Viz také
* třída [`Color`](/slides/python-net/cs/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)