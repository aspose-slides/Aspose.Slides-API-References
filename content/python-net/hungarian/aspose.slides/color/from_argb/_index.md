---
title: from_argb method
second_title: Aspose.Slides Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Létrehoz egy színt egy 32 bites ARGB értékből.

### Visszatérési érték

A megadott értékből létrehozott szín.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| argb | **int** | A 32 bites ARGB értéket (előjeles vagy előjel nélküli) meghatározó érték. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **ValueError** | Az alkotóelem értéke 0-nál kisebb vagy 255-nél nagyobb. |
| **TypeError** | Hibás számú vagy típusú argumentum. |


## from_argb(alpha, base_color) {#int-color}
Létrehoz egy színt a megadott alfa értékből és az alap színből.

### Visszatérési érték

A megadott értékekből létrehozott szín.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| alpha | **int** | Az alfa komponens értéke. Az érvényes értékek 0 és 255 között vannak. |
| base_color | [`Color`](/slides/python-net/hu/aspose.slides/color) | Az a szín, amelyből az új színt létrehozzuk. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **ValueError** | Az alkotóelem értéke 0-nál kisebb vagy 255-nél nagyobb. |
| **TypeError** | Hibás számú vagy típusú argumentum. |


## from_argb(red, green, blue) {#int-int-int}
Létrehoz egy átlátszatlan színt (az alfa 255) a megadott piros, zöld és kék értékekből.

### Visszatérési érték

A megadott értékekből létrehozott szín.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| red | **int** | A piros komponens értéke. Az érvényes értékek 0 és 255 között vannak. |
| green | **int** | A zöld komponens értéke. Az érvényes értékek 0 és 255 között vannak. |
| blue | **int** | A kék komponens értéke. Az érvényes értékek 0 és 255 között vannak. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **ValueError** | Az alkotóelem értéke 0-nál kisebb vagy 255-nél nagyobb. |
| **TypeError** | Hibás számú vagy típusú argumentum. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Létrehoz egy színt a négy ARGB komponens (alfa, piros, zöld és kék) értékeiből.

### Visszatérési érték

A megadott értékekből létrehozott szín.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| alpha | **int** | Az alfa komponens értéke. Az érvényes értékek 0 és 255 között vannak. |
| red | **int** | A piros komponens értéke. Az érvényes értékek 0 és 255 között vannak. |
| green | **int** | A zöld komponens értéke. Az érvényes értékek 0 és 255 között vannak. |
| blue | **int** | A kék komponens értéke. Az érvényes értékek 0 és 255 között vannak. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **ValueError** | Az alkotóelem értéke 0-nál kisebb vagy 255-nél nagyobb. |
| **TypeError** | Hibás számú vagy típusú argumentum. |



### Lásd még
* osztály [`Color`](/slides/python-net/hu/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)