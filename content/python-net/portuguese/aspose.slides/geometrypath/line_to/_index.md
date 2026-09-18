---
title: line_to method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
Adiciona uma linha ao final do caminho


```python
def line_to(self, point):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Ponto final da linha |


## line_to(self, x, y) {#float-float}
Adiciona uma linha ao final do caminho


```python
def line_to(self, x, y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | Coordenada X do ponto final da linha |
| y | **float** | Coordenada Y do ponto final da linha |


## line_to(self, point, index) {#asposepydrawingpointf-int}
Adiciona uma linha ao local especificado do caminho


```python
def line_to(self, point, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Ponto final |
| index | **int** | Índice do segmento em PathData |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | O índice do segmento está fora do intervalo de PathData |


## line_to(self, x, y, index) {#float-float-int}
Adiciona uma linha ao local especificado do caminho


```python
def line_to(self, x, y, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | Coordenada X do ponto |
| y | **float** | Coordenada Y do ponto |
| index | **int** | Índice do segmento em PathData |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | O índice do segmento está fora do intervalo de PathData |



### Veja Também
* classe [`GeometryPath`](/slides/python-net/pt/aspose.slides/geometrypath)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)