---
title: cubic_bezier_to method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Adiciona curva Bezier cúbica ao final do caminho


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Primeiro ponto de direção |
| point2 | **aspose.slides.PointF** | Segundo ponto de direção |
| point3 | **aspose.slides.PointF** | Ponto final |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Adiciona curva Bezier cúbica ao local especificado do caminho


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Primeiro ponto de direção |
| point2 | **aspose.slides.PointF** | Segundo ponto de direção |
| point3 | **aspose.slides.PointF** | Ponto final |
| index | **int** | Índice do segmento em PathData |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | O índice do segmento está fora do intervalo de PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Adiciona curva Bezier cúbica ao final do caminho


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x1 | **float** | Coordenada X do primeiro ponto de direção |
| y1 | **float** | Coordenada Y do primeiro ponto de direção |
| x2 | **float** | Coordenada X do segundo ponto de direção |
| y2 | **float** | Coordenada Y do segundo ponto de direção |
| x3 | **float** | Coordenada X do ponto final |
| y3 | **float** | Coordenada Y do ponto final |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Adiciona curva Bezier cúbica ao local especificado do caminho


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x1 | **float** | Coordenada X do primeiro ponto de direção |
| y1 | **float** | Coordenada Y do primeiro ponto de direção |
| x2 | **float** | Coordenada X do segundo ponto de direção |
| y2 | **float** | Coordenada Y do segundo ponto de direção |
| x3 | **float** | Coordenada X do ponto final |
| y3 | **float** | Coordenada Y do ponto final |
| index | **int** | Índice do segmento em PathData |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | O índice do segmento está fora do intervalo de PathData |



### Veja também
* classe [`IGeometryPath`](/slides/python-net/pt/aspose.slides/igeometrypath)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)