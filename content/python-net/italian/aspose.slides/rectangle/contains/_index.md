---
title: contains method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Determina se il punto specificato è contenuto all'interno di questo rettangolo.

### Restituisce

`True` se il punto è contenuto all'interno di questo rettangolo; altrimenti, `False`.



```python
def contains(self, point):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/it/aspose.slides/point) | Il punto da testare. Qualsiasi oggetto con attributi `x` e `y` è accettato. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **TypeError** | Numero di argomenti errato. |


## contains(self, rect) {#rectangle}
Determina se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questo rettangolo.

### Restituisce

`True` se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questo rettangolo; altrimenti, `False`.



```python
def contains(self, rect):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/it/aspose.slides/rectangle) | Il rettangolo da testare. Qualsiasi oggetto con attributi `x`, `y`, `width` e `height` è accettato. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **TypeError** | Numero di argomenti errato. |


## contains(self, x, y) {#int-int}
Determina se il punto specificato è contenuto all'interno di questo rettangolo.

### Restituisce

`True` se il punto definito da `x` e `y` è contenuto all'interno di questo rettangolo; altrimenti, `False`.



```python
def contains(self, x, y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | **int** | La coordinata x del punto da testare. |
| y | **int** | La coordinata y del punto da testare. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **TypeError** | Numero di argomenti errato. |



### Vedi anche
* classe [`Point`](/slides/python-net/it/aspose.slides/point)
* classe [`Rectangle`](/slides/python-net/it/aspose.slides/rectangle)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)