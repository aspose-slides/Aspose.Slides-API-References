---
title: from_argb method
second_title: Aspose.Slides dla Pythona poprzez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Tworzy kolor z 32-bitowej wartości ARGB.

### Zwraca

Kolor utworzony z podanej wartości.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| argb | **int** | Wartość określająca 32-bitową wartość ARGB (ze znakiem lub bez znaku). |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **ValueError** | Wartość składnika jest mniejsza niż 0 lub większa niż 255. |
| **TypeError** | Nieprawidłowa liczba lub typ argumentów. |


## from_argb(alpha, base_color) {#int-color}
Tworzy kolor z podanej wartości alfa i koloru bazowego.

### Zwraca

Kolor utworzony z podanych wartości.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| alpha | **int** | Wartość składnika alfa. Dopuszczalne wartości to od 0 do 255. |
| base_color | [`Color`](/slides/python-net/pl/aspose.slides/color) | Kolor, z którego ma zostać utworzony nowy kolor. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **ValueError** | Wartość składnika jest mniejsza niż 0 lub większa niż 255. |
| **TypeError** | Nieprawidłowa liczba lub typ argumentów. |


## from_argb(red, green, blue) {#int-int-int}
Tworzy nieprzezroczysty kolor (alpha wynosi 255) z podanych wartości czerwonego, zielonego i niebieskiego.

### Zwraca

Kolor utworzony z podanych wartości.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| red | **int** | Wartość składnika czerwonego. Dopuszczalne wartości to od 0 do 255. |
| green | **int** | Wartość składnika zielonego. Dopuszczalne wartości to od 0 do 255. |
| blue | **int** | Wartość składnika niebieskiego. Dopuszczalne wartości to od 0 do 255. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **ValueError** | Wartość składnika jest mniejsza niż 0 lub większa niż 255. |
| **TypeError** | Nieprawidłowa liczba lub typ argumentów. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Tworzy kolor z czterech wartości składników ARGB (alpha, czerwony, zielony i niebieski).

### Zwraca

Kolor utworzony z podanych wartości.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| alpha | **int** | Wartość składnika alfa. Dopuszczalne wartości to od 0 do 255. |
| red | **int** | Wartość składnika czerwonego. Dopuszczalne wartości to od 0 do 255. |
| green | **int** | Wartość składnika zielonego. Dopuszczalne wartości to od 0 do 255. |
| blue | **int** | Wartość składnika niebieskiego. Dopuszczalne wartości to od 0 do 255. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **ValueError** | Wartość składnika jest mniejsza niż 0 lub większa niż 255. |
| **TypeError** | Nieprawidłowa liczba lub typ argumentów. |



### Zobacz także
* klasa [`Color`](/slides/python-net/pl/aspose.slides/color)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)