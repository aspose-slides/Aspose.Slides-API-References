---
title: quadratic_bezier_to method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Adiciona curva Bezier quadrática ao final do caminho


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Ponto de direção |
| point2 | **aspose.slides.PointF** | Ponto final |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Adiciona curva Bezier quadrática ao local especificado do caminho


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Ponto de direção |
| point2 | **aspose.slides.PointF** | Ponto final |
| index | **int** | Índice do segmento em PathData |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Índice do segmento está fora do intervalo de PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Adiciona curva Bezier quadrática ao final do caminho


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
Adiciona curva Bezier quadrática ao local especificado do caminho


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Índice do segmento está fora do intervalo de PathData |



### Veja Também
* classe [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)