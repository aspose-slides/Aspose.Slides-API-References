---
title: add_clone method
second_title: Aspose.Slides para Python via .NET API Reference
description: 
type: docs
url: /pt/aspose.slides/igloballayoutslidecollection/add_clone/
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

Ao clonar um layout entre apresentações diferentes, o mestre do layout também pode ser clonado para manter a formatação da origem. Um registro interno é usado para rastrear mestres clonados automaticamente, a fim de evitar a criação de múltiplos clones do mesmo slide mestre. A clonagem manual de slides mestres não será impedida nem registrada.


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
| dest_master | [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide) | Slide mestre para um novo layout. |

### Observações

O novo layout será vinculado ao mestre definido na apresentação de destino. Assim, isto é análogo a copiar/colar com a opção "Use Destination Theme" no PowerPoint.



### Veja Também
* classe [`IGlobalLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/igloballayoutslidecollection)
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)