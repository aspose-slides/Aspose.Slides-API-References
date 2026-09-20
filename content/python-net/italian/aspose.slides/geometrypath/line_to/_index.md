---
title: line_to method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
Aggiunge una linea alla fine del percorso


```python
def line_to(self, point):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Punto finale della linea |


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


## line_to(self, point, index) {#asposepydrawingpointf-int}
Aggiunge una linea al punto specificato del percorso


```python
def line_to(self, point, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Punto finale |
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
* classe [`GeometryPath`](/slides/python-net/it/aspose.slides/geometrypath)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)