---
title: line_to method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
Adiciona uma linha ao final do caminho


```python
def line_to(self, point):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/pt/aspose.slides/pointf) | Ponto final da linha |


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


## line_to(self, point, index) {#asposeslidespointf-int}
Adiciona linha ao local especificado do caminho


```python
def line_to(self, point, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/pt/aspose.slides/pointf) | Ponto final |
| index | **int** | Índice do segmento em PathData |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Índice do segmento está fora do intervalo de PathData |


## line_to(self, x, y, index) {#float-float-int}
Adiciona linha ao local especificado do caminho


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Índice do segmento está fora do intervalo de PathData |



### Veja Também
* classe [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath)
* classe [`PointF`](/slides/python-net/pt/aspose.slides/pointf)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)