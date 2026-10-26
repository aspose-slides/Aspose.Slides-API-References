---
title: remove_node method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Remover nó ou subnó por índice


```python
def remove_node(self, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Índice baseado em zero do nó |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index é menor que 0.  -ou- index é igual ou maior que a contagem de irmãos |


## remove_node(self, node) {#ismartartnode}
Remover nó ou subnó


```python
def remove_node(self, node):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/pt/aspose.slides.smartart/ismartartnode) | Nó a remover |



### Veja Também
* classe [`ISmartArtNode`](/slides/python-net/pt/aspose.slides.smartart/ismartartnode)
* classe [`SmartArtNodeCollection`](/slides/python-net/pt/aspose.slides.smartart/smartartnodecollection)
* módulo [`aspose.slides.smartart`](/slides/python-net/pt/aspose.slides.smartart)
* biblioteca [`Aspose.Slides`](/slides/python-net)