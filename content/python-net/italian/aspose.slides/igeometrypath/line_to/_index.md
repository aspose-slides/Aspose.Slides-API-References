---
title: line_to method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
Aggiunge una linea alla fine del percorso


```python
def line_to(self, point):
    ...
```



| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/it/aspose.slides/pointf) | Punto finale della linea |


## line_to(self, x, y) {#float-float}
Aggiunge una linea alla fine del percorso


```python
def line_to(self, x, y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | **float** | Coordinata X del punto finale della linea |
| y | **float** | Coordinata Y del punto finale della linea |


## line_to(self, point, index) {#asposeslidespointf-int}
Aggiunge una linea al punto specificato del percorso


```python
def line_to(self, point, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/it/aspose.slides/pointf) | Punto finale |
| index | **int** | Indice del segmento in PathData |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'indice del segmento è fuori dall'intervallo di PathData |


## line_to(self, x, y, index) {#float-float-int}
Aggiunge una linea al punto specificato del percorso


```python
def line_to(self, x, y, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | **float** | Coordinata X del punto |
| y | **float** | Coordinata Y del punto |
| index | **int** | Indice del segmento in PathData |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'indice del segmento è fuori dall'intervallo di PathData |



### Vedi anche
* classe [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath)
* classe [`PointF`](/slides/python-net/it/aspose.slides/pointf)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)