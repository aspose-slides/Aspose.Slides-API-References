---
title: add_clone method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Přidá kopii zadaného snímku na konec kolekce.

### Vrací

Nový snímek.



```python
def add_clone(self, source_slide):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Snímek ke klonování. |

### Poznámky

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
Přidá kopii zadaného snímku na konec zadané sekce.

### Vrací

Nový snímek.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Snímek ke klonování. |
| section | [`ISection`](/slides/python-net/cs/aspose.slides/isection) | Sekce pro nový snímek. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Přidá kopii zadaného snímku na konec kolekce.

### Vrací

Nový snímek.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Snímek ke klonování. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Rozvržení snímku pro nový snímek. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Přidá kopii zadaného zdrojového snímku na konec kolekce.
            Appropriate layout will be selected automatically from the specified 
            master (appropriate layout is the layout with the same Type or Name as 
            of layout of the source slide). If there is no appropriate layout then
            layout of the source slide will be cloned (if allowCloneMissingLayout 
            is true) or PptxEditException will be thrown (if allowCloneMissingLayout
            is false).

### Vrací

Nový snímek.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Snímek ke klonování. |
| dest_master | [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide) | Master snímek pro nový snímek. |
| allow_clone_missing_layout | **bool** | Pokud v určeném masteru neexistuje vhodné rozvržení, bude rozvržení <br/><br/>            zdrojového snímku klonováno (pokud je allowCloneMissingLayout nastaveno na true) nebo <br/><br/>            bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout nastaveno na false). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud v určeném masteru neexistuje vhodné rozvržení a <br/>            allowCloneMissingLayout je false. |



### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide)
* třída [`ISection`](/slides/python-net/cs/aspose.slides/isection)
* třída [`ISlide`](/slides/python-net/cs/aspose.slides/islide)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* třída [`SlideCollection`](/slides/python-net/cs/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)