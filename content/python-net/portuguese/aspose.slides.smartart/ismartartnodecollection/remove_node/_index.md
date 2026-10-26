---
title: remove_node method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Remove nó ou subnó por índice.

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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | o índice é menor que 0.  -ou- o índice é igual ou maior que a contagem de irmãos. |

## remove_node(self, node_obj) {#ismartartnode}
Remove nó ou subnó.

```python
def remove_node(self, node_obj):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/pt/aspose.slides.smartart/ismartartnode) | Nó a ser removido. |

### Veja Também
* classe [`ISmartArtNode`](/slides/python-net/pt/aspose.slides.smartart/ismartartnode)
* classe [`ISmartArtNodeCollection`](/slides/python-net/pt/aspose.slides.smartart/ismartartnodecollection)
* módulo [`aspose.slides.smartart`](/slides/python-net/pt/aspose.slides.smartart)
* biblioteca [`Aspose.Slides`](/slides/python-net)