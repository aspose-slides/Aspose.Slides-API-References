---
title: from_argb method
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
Crea un colore a partire da un valore ARGB a 32 bit.

### Restituisce

Il colore creato dal valore specificato.



```python
@staticmethod
def from_argb(argb):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| argb | **int** | Un valore che specifica il valore ARGB a 32 bit (con segno o senza segno). |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **ValueError** | Un valore di componente è inferiore a 0 o superiore a 255. |
| **TypeError** | Numero o tipo di argomenti errati. |


## from_argb(alpha, base_color) {#int-color}
Crea un colore dal valore alfa specificato e dal colore di base.

### Restituisce

Il colore creato dai valori specificati.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| alpha | **int** | Il valore del componente alfa. I valori validi sono da 0 a 255. |
| base_color | [`Color`](/slides/python-net/it/aspose.slides/color) | Il colore dal quale creare il nuovo colore. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **ValueError** | Un valore di componente è inferiore a 0 o superiore a 255. |
| **TypeError** | Numero o tipo di argomenti errati. |


## from_argb(red, green, blue) {#int-int-int}
Crea un colore opaco (alpha è 255) dai valori rosso, verde e blu specificati.

### Restituisce

Il colore creato dai valori specificati.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| red | **int** | Il valore del componente rosso. I valori validi sono da 0 a 255. |
| green | **int** | Il valore del componente verde. I valori validi sono da 0 a 255. |
| blue | **int** | Il valore del componente blu. I valori validi sono da 0 a 255. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **ValueError** | Un valore di componente è inferiore a 0 o superiore a 255. |
| **TypeError** | Numero o tipo di argomenti errati. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
Crea un colore dai quattro valori dei componenti ARGB (alpha, rosso, verde e blu).

### Restituisce

Il colore creato dai valori specificati.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| alpha | **int** | Il valore del componente alfa. I valori validi sono da 0 a 255. |
| red | **int** | Il valore del componente rosso. I valori validi sono da 0 a 255. |
| green | **int** | Il valore del componente verde. I valori validi sono da 0 a 255. |
| blue | **int** | Il valore del componente blu. I valori validi sono da 0 a 255. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **ValueError** | Un valore di componente è inferiore a 0 o superiore a 255. |
| **TypeError** | Numero o tipo di argomenti errati. |



### Vedi anche
* classe [`Color`](/slides/python-net/it/aspose.slides/color)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)