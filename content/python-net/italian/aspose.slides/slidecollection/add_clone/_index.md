---
title: add_clone method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

### Restituisce

Nuova diapositiva.



```python
def add_clone(self, source_slide):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva da clonare. |

### Osservazioni

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of 
            multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
            **Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** or
            **Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides,
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** or
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** for cloning layouts and
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## add_clone(self, source_slide, section) {#islide-isection}
Aggiunge una copia di una diapositiva specificata alla fine della sezione specificata.

### Restituisce

Nuova diapositiva.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva da clonare. |
| section | [`ISection`](/slides/python-net/it/aspose.slides/isection) | Sezione per una nuova diapositiva. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

### Restituisce

Nuova diapositiva.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva da clonare. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide) | Diapositiva layout per una nuova diapositiva. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Aggiunge una copia di una diapositiva sorgente specificata alla fine della raccolta.
            Appropriate layout will be selected automatically from the specified 
            master (appropriate layout is the layout with the same Type or Name as 
            of layout of the source slide). If there is no appropriate layout then
            layout of the source slide will be cloned (if allowCloneMissingLayout 
            is true) or PptxEditException will be thrown (if allowCloneMissingLayout
            is false).

### Restituisce

Nuova diapositiva.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Diapositiva da clonare. |
| dest_master | [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide) | Diapositiva master per una nuova diapositiva. |
| allow_clone_missing_layout | **bool** | Se non esiste un layout appropriato nel master specificato, allora il layout della <br/><br/>            diapositiva sorgente verrà clonato (se allowCloneMissingLayout è true) o <br/><br/>            PptxEditException verrà sollevata (se allowCloneMissingLayout è false). |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Sollevata se non esiste un layout appropriato nel master specificato e allowCloneMissingLayout è false. |



### Vedi anche
* classe [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide)
* classe [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide)
* classe [`ISection`](/slides/python-net/it/aspose.slides/isection)
* classe [`ISlide`](/slides/python-net/it/aspose.slides/islide)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* classe [`SlideCollection`](/slides/python-net/it/aspose.slides/slidecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)