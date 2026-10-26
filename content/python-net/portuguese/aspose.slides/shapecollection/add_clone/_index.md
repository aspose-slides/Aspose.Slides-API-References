---
title: add_clone method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.  
A forma clonada mantém a posição e o tamanho da original.

### Retorna

O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) recém-criado.



```python
def add_clone(self, source_shape):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) a ser clonado. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.  
A nova forma mantém a largura e a altura da `source_shape`.

### Retorna

O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) recém-criado.



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | A forma a ser clonada. |
| x | **float** | A coordenada x da moldura da nova forma, em pontos. |
| y | **float** | A coordenada y da moldura da nova forma, em pontos. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.

### Retorna

O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) recém-criado.



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | A forma a ser clonada. |
| x | **float** | A coordenada x da moldura da nova forma, em pontos. |
| y | **float** | A coordenada y da moldura da nova forma, em pontos. |
| width | **float** | A largura da moldura da nova forma, em pontos. |
| height | **float** | A altura da moldura da nova forma, em pontos. |



### Consulte Também
* classe [`IShape`](/slides/python-net/pt/aspose.slides/ishape)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)