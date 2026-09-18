---
title: add_clone method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Adiciona uma cópia de um slide de layout especificado ao final da coleção.

### Retorno

Slide adicionado.



```python
def add_clone(self, source_layout):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide) | Slide a ser clonado. |

### Observações

1) O novo layout será vinculado ao slide mestre pai desta coleção de slides de layout.  
   Portanto, isso é análogo a copiar/colar com a opção "Use Destination Theme" no PowerPoint.  
2) Análogo a este método é o método **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** acessado com a propriedade [`IPresentation.layout_slides`](/slides/python-net/pt/aspose.slides/ipresentation/layout_slides).



### Ver também
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)