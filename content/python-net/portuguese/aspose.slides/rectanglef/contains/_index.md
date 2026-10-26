---
title: contains method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Determina se o ponto especificado está contido dentro deste retângulo.

### Retorna

`True` se o ponto está contido dentro deste retângulo; caso contrário, `False`.



```python
def contains(self, point):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/pt/aspose.slides/pointf) | O ponto a ser testado. Qualquer objeto com `x` e `y` atributos é aceito. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **TypeError** | Número incorreto de argumentos. |


## contains(self, rect) {#rectanglef}
Determina se a região retangular representada por `rect` está totalmente contida dentro deste retângulo.

### Retorna

`True` se a região retangular representada por `rect` está totalmente contida dentro deste retângulo; caso contrário, `False`.



```python
def contains(self, rect):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/pt/aspose.slides/rectanglef) | O retângulo a ser testado. Qualquer objeto com `x`, `y`, `width` e `height` atributos é aceito. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **TypeError** | Número incorreto de argumentos. |


## contains(self, x, y) {#float-float}
Determina se o ponto especificado está contido dentro deste retângulo.

### Retorna

`True` se o ponto definido por `x` e `y` está contido dentro deste retângulo; caso contrário, `False`.



```python
def contains(self, x, y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x do ponto a ser testado. |
| y | **float** | A coordenada y do ponto a ser testado. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **TypeError** | Número incorreto de argumentos. |



### Veja Também
* classe [`PointF`](/slides/python-net/pt/aspose.slides/pointf)
* classe [`RectangleF`](/slides/python-net/pt/aspose.slides/rectanglef)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)