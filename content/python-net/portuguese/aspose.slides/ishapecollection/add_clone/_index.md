---
title: add_clone method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.
A forma clonada mantém a posição e o tamanho originais.

### Retorno

O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) recém-criado.



```python
def add_clone(self, source_shape):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | A [`IShape`](/slides/python-net/pt/aspose.slides/ishape) a ser clonada. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.
A nova forma mantém a largura e a altura da `source_shape`.

### Retorno

O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) recém-criado.



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | A [`IShape`](/slides/python-net/pt/aspose.slides/ishape) a ser clonada. |
| x | **float** | A coordenada x da moldura da forma clonada, em pontos. |
| y | **float** | A coordenada y da moldura da forma clonada, em pontos. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.

### Retorno

O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) recém-criado.



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | A forma a ser clonada. |
| x | **float** | A coordenada x da moldura da forma clonada, em pontos. |
| y | **float** | A coordenada y da moldura da forma clonada, em pontos. |
| width | **float** | A largura da moldura da forma clonada, em pontos. |
| height | **float** | A altura da moldura da forma clonada, em pontos. |



### Ver Também
* classe [`IShape`](/slides/python-net/pt/aspose.slides/ishape)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)