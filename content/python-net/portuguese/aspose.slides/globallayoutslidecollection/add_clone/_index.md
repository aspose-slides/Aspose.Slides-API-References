---
title: add_clone method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Adiciona uma cópia de um slide de layout especificado à apresentação.

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

Ao clonar um layout entre diferentes apresentações, o master do layout também pode ser clonado para manter a formatação da origem. Um registro interno é usado para rastrear masters clonados automaticamente, a fim de impedir a criação de múltiplos clones do mesmo slide master. A clonagem manual de slides master não será impedida nem registrada.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Adiciona uma cópia de um slide de layout especificado à apresentação.

### Retorno

Slide adicionado.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide) | Slide a ser clonado. |
| dest_master | [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide) | Slide master para um novo layout. |

### Observações

1) O novo layout será vinculado ao master definido na apresentação de destino. Portanto, isso é análogo a copiar/colar com a opção "Use Destination Theme" no PowerPoint.  
2) Análogo a este método é o método **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** acessado com [`IMasterSlide.layout_slides`](/slides/python-net/pt/aspose.slides/imasterslide/layout_slides) propriedade.



### Veja também
* classe [`GlobalLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection)
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)