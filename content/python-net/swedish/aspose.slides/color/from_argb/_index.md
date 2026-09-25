---
title: from_argb method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Skapar en färg från ett 32-bitars ARGB-värde.

### Returns
Färgen som skapats från det angivna värdet.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| argb | **int** | Ett värde som specificerar det 32-bitars ARGB-värdet (signerat eller osignerat). |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | Ett komponentvärde är mindre än 0 eller större än 255. |
| **TypeError** | Fel antal eller fel typ av argument. |


## from_argb(alpha, base_color) {#int-color}
Skapar en färg från det angivna alfa-värdet och basfärgen.

### Returns
Färgen som skapats från de angivna värdena.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alpha | **int** | Alfa-komponentens värde. Giltiga värden är 0 till 255. |
| base_color | [`Color`](/slides/python-net/sv/aspose.slides/color) | Färgen som den nya färgen ska baseras på. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | Ett komponentvärde är mindre än 0 eller större än 255. |
| **TypeError** | Fel antal eller fel typ av argument. |


## from_argb(red, green, blue) {#int-int-int}
Skapar en ogenomskinlig färg (alfa är 255) från de angivna röd-, grönt- och blåvärdena.

### Returns
Färgen som skapats från de angivna värdena.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| red | **int** | Den röda komponentens värde. Giltiga värden är 0 till 255. |
| green | **int** | Den gröna komponentens värde. Giltiga värden är 0 till 255. |
| blue | **int** | Den blå komponentens värde. Giltiga värden är 0 till 255. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | Ett komponentvärde är mindre än 0 eller större än 255. |
| **TypeError** | Fel antal eller fel typ av argument. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Skapar en färg från de fyra ARGB-komponenterna (alfa, röd, grön och blå) värdena.

### Returns
Färgen som skapats från de angivna värdena.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alpha | **int** | Alfa-komponentens värde. Giltiga värden är 0 till 255. |
| red | **int** | Den röda komponentens värde. Giltiga värden är 0 till 255. |
| green | **int** | Den gröna komponentens värde. Giltiga värden är 0 till 255. |
| blue | **int** | Den blå komponentens värde. Giltiga värden är 0 till 255. |

### Exceptions

| Exception | Description |
| :- | :- |
| **ValueError** | Ett komponentvärde är mindre än 0 eller större än 255. |
| **TypeError** | Fel antal eller fel typ av argument. |



### See Also
* klass [`Color`](/slides/python-net/sv/aspose.slides/color)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)