---
title: insert_clone method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Insere uma cópia de um slide de layout especificado na posição especificada da coleção.

### Retorno

Slide inserido.



```python
def insert_clone(self, index, source_layout):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | Índice do novo slide. |
| source_layout | [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide) | Slide a clonar. |

### Observações

O novo layout será vinculado ao slide mestre pai para esta coleção de slides de layout. Portanto, isso é análogo a copiar/colar com a opção "Use Destination Theme" no PowerPoint.



### Ver também
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)