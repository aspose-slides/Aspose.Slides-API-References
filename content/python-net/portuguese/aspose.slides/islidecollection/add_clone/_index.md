---
title: add_clone method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Adiciona uma cópia de um slide especificado ao final da coleção.

### Retorna

Novo slide.



```python
def add_clone(self, source_slide):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide a ser clonado. |

### Observações

Ao clonar um slide entre diferentes apresentações, o mestre do slide também pode ser clonado.
Internal registry is used to track automatically cloned masters to prevent creation of 
multiple clones of the same master slide.
Manual cloning of master slides will be neither prevented nor registered.
If you need more control over cloning process use
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** or
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides,
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** or
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** for cloning layouts and
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## add_clone(self, source_slide, section) {#islide-isection}
Adiciona uma cópia de um slide especificado ao final da seção especificada.

### Retorna

Novo slide.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide a ser clonado. |
| section | [`ISection`](/slides/python-net/pt/aspose.slides/isection) | Seção para um novo slide. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Adiciona uma cópia de um slide especificado ao final da coleção.

### Retorna

Novo slide.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide a ser clonado. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide) | Slide de layout para um novo slide. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Adiciona uma cópia de um slide de origem especificado ao final da coleção.
            O layout apropriado será selecionado automaticamente a partir do
            mestre especificado (o layout apropriado é o layout com o mesmo Tipo ou Nome do
            layout do slide de origem). Se não houver um layout apropriado,
            o layout do slide de origem será clonado (se allowCloneMissingLayout
            for true) ou será lançada uma PptxEditException (se allowCloneMissingLayout
            for false).

### Retorna

Novo slide.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide a ser clonado. |
| dest_master | [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide) | Slide mestre para um novo slide. |
| allow_clone_missing_layout | **bool** | Se não houver um layout apropriado no mestre especificado, então o layout do <br/><br/>            slide de origem será clonado (se allowCloneMissingLayout for true) ou <br/><br/>            PptxEditException será lançada (se allowCloneMissingLayout for false). |

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançada se não houver um layout apropriado no mestre especificado e <br/>            allowCloneMissingLayout for false. |



### Veja Também
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide)
* classe [`ISection`](/slides/python-net/pt/aspose.slides/isection)
* classe [`ISlide`](/slides/python-net/pt/aspose.slides/islide)
* classe [`ISlideCollection`](/slides/python-net/pt/aspose.slides/islidecollection)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)