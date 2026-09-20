---
title: line_to method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/igeometrypath/line_to/
weight: 40
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
* classe [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)