---
title: contains method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Determina se o ponto especificado está contido dentro deste retângulo.

### Retorna

`True` if the point is contained within this rectangle; otherwise, `False`.



```python
def contains(self, point):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/pt/aspose.slides/point) | O ponto a ser testado. Qualquer objeto com atributos `x` e `y` é aceito. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, rect) {#rectangle}
Determina se a região retangular representada por `rect` está completamente contida dentro deste retângulo.

### Retorna

`True` if the rectangular region represented by `rect` is entirely contained within this rectangle; otherwise, `False`.



```python
def contains(self, rect):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/pt/aspose.slides/rectangle) | O retângulo a ser testado. Qualquer objeto com atributos `x`, `y`, `width` e `height` é aceito. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, x, y) {#int-int}
Determina se o ponto especificado está contido dentro deste retângulo.

### Retorna

`True` if the point defined by `x` and `y` is contained within this rectangle; otherwise, `False`.



```python
def contains(self, x, y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **int** | A coordenada x do ponto a ser testado. |
| y | **int** | A coordenada y do ponto a ser testado. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **TypeError** | Wrong number of arguments. |



### Veja Também
* classe [`Point`](/slides/python-net/pt/aspose.slides/point)
* classe [`Rectangle`](/slides/python-net/pt/aspose.slides/rectangle)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)