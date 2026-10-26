---
title: insert_clone method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado.  
A forma clonada mantém a posição e o tamanho originais.

### Retorna

O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) recém-criado.



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir a forma clonada. |
| source_shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) a ser clonado. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado.  
A nova forma mantém a largura e a altura do `source_shape`.

### Retorna

O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) recém-criado.



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir a forma clonada. |
| source_shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) a ser clonado. |
| x | **float** | A coordenada x da moldura da forma clonada, em pontos. |
| y | **float** | A coordenada y da moldura da forma clonada, em pontos. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado.

### Retorna

O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) recém-criado.



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir a forma clonada. |
| source_shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | O [`IShape`](/slides/python-net/pt/aspose.slides/ishape) a ser clonado. |
| x | **float** | A coordenada x da moldura da forma clonada, em pontos. |
| y | **float** | A coordenada y da moldura da forma clonada, em pontos. |
| width | **float** | A largura da moldura da forma clonada, em pontos. |
| height | **float** | A altura da moldura da forma clonada, em pontos. |



### Veja Também
* classe [`IShape`](/slides/python-net/pt/aspose.slides/ishape)
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)