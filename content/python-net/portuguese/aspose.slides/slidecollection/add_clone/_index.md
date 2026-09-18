---
title: add_clone method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Adiciona uma cópia de um slide específico ao final da coleção.

### Retorna

Novo slide.



```python
def add_clone(self, source_slide):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide to clone. |

### Observações

Ao clonar um slide entre apresentações diferentes, o mestre do slide também pode ser clonado.
            Um registro interno é usado para rastrear mestres clonados automaticamente e evitar a criação de
            múltiplas cópias do mesmo slide mestre.
            A clonagem manual de slides mestres não será impedida nem registrada.
            Se precisar de mais controle sobre o processo de clonagem, use
            **Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** ou
            **Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** para clonar slides,
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** ou
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** para clonar layouts e
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** para clonar mestres.


## add_clone(self, source_slide, section) {#islide-isection}
Adiciona uma cópia de um slide específico ao final da seção especificada.

### Retorna

Novo slide.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide to clone. |
| section | [`ISection`](/slides/python-net/pt/aspose.slides/isection) | Section for a new slide. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Adiciona uma cópia de um slide específico ao final da coleção.

### Retorna

Novo slide.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide to clone. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide) | Layout slide for a new slide. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Adiciona uma cópia de um slide de origem especificado ao final da coleção.
            O layout apropriado será selecionado automaticamente a partir do 
            mestre especificado (o layout apropriado é o layout com o mesmo Tipo ou Nome que 
            o layout do slide de origem). Se não houver um layout apropriado, o
            layout do slide de origem será clonado (se allowCloneMissingLayout 
            for verdadeiro) ou será lançada uma PptxEditException (se allowCloneMissingLayout
            for falso).

### Retorna

Novo slide.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide to clone. |
| dest_master | [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide) | Master slide for a new slide. |
| allow_clone_missing_layout | **bool** | Se não houver um layout apropriado no mestre especificado então o layout do <br/><br/>            slide de origem será clonado (se allowCloneMissingLayout for true) ou <br/><br/>            PptxEditException será lançada (se allowCloneMissingLayout for false). |

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançada se não houver um layout apropriado no mestre especificado e <br/>            allowCloneMissingLayout for false. |



### Veja Também
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/pt/aspose.slides/imasterslide)
* classe [`ISection`](/slides/python-net/pt/aspose.slides/isection)
* classe [`ISlide`](/slides/python-net/pt/aspose.slides/islide)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* classe [`SlideCollection`](/slides/python-net/pt/aspose.slides/slidecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)