---
title: contains method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Determina se il punto specificato è contenuto all'interno di questo rettangolo.

### Restituisce

`True` se il punto è contenuto all'interno di questo rettangolo; altrimenti, `False`.



```python
def contains(self, point):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/it/aspose.slides/pointf) | Il punto da testare. Qualsiasi oggetto con attributi `x` e `y` è accettato. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **TypeError** | Numero di argomenti errato. |


## contains(self, rect) {#rectanglef}
Determina se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questo rettangolo.

### Restituisce

`True` se la regione rettangolare rappresentata da `rect` è interamente contenuta all'interno di questo rettangolo; altrimenti, `False`.



```python
def contains(self, rect):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/it/aspose.slides/rectanglef) | Il rettangolo da testare. Qualsiasi oggetto con attributi `x`, `y`, `width` e `height` è accettato. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **TypeError** | Numero di argomenti errato. |


## contains(self, x, y) {#float-float}
Determina se il punto specificato è contenuto all'interno di questo rettangolo.

### Restituisce

`True` se il punto definito da `x` e `y` è contenuto all'interno di questo rettangolo; altrimenti, `False`.



```python
def contains(self, x, y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | **float** | La coordinata x del punto da testare. |
| y | **float** | La coordinata y del punto da testare. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **TypeError** | Numero di argomenti errato. |



### Vedi anche
* classe [`PointF`](/slides/python-net/it/aspose.slides/pointf)
* classe [`RectangleF`](/slides/python-net/it/aspose.slides/rectanglef)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)