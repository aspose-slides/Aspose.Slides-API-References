---
title: quadratic_bezier_to method
second_title: Aspose.Slides para Python via .NET - Referência da API
description: 
type: docs
url: /pt/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Adiciona curva quadrática de Bezier ao final do caminho


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/pt/aspose.slides/pointf) | Ponto de direção |
| point2 | [`PointF`](/slides/python-net/pt/aspose.slides/pointf) | Ponto final |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Adiciona curva quadrática de Bezier ao local especificado do caminho


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/pt/aspose.slides/pointf) | Ponto de direção |
| point2 | [`PointF`](/slides/python-net/pt/aspose.slides/pointf) | Ponto final |
| index | **int** | Índice do segmento em PathData |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | O índice do segmento está fora do intervalo de PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Adiciona curva quadrática de Bezier ao final do caminho


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x1 | **float** | Coordenada X do ponto de direção |
| y1 | **float** | Coordenada Y do ponto de direção |
| x2 | **float** | Coordenada X do ponto final |
| y2 | **float** | Coordenada Y do ponto final |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Adiciona curva quadrática de Bezier ao local especificado do caminho


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x1 | **float** | Coordenada X do ponto de direção |
| y1 | **float** | Coordenada Y do ponto de direção |
| x2 | **float** | Coordenada X do ponto final |
| y2 | **float** | Coordenada Y do ponto final |
| index | **int** | Índice do segmento em PathData |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | O índice do segmento está fora do intervalo de PathData |



### Veja Também
* classe [`GeometryPath`](/slides/python-net/pt/aspose.slides/geometrypath)
* classe [`PointF`](/slides/python-net/pt/aspose.slides/pointf)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)