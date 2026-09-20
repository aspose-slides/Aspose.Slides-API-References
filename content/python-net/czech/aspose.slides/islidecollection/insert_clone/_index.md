---
title: insert_clone method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Vloží kopii určeného snímku na zadanou pozici v kolekci.

### Vrací

Vložený snímek.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index nového snímku. |
| source_slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Snímek ke klonování. |

### Poznámky

When cloning a slide between different presentations slide's master can be cloned too.
            Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.
            Manual cloning of master slides will be neither prevented nor registered.
            If you need more control over cloning process use
            **Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** or
            **Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides and
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Vloží kopii určeného snímku na zadanou pozici v kolekci.

### Vrací

Vložený snímek.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index nového snímku. |
| source_slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Snímek ke klonování. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Rozložení snímku pro nový snímek. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Vloží kopii určeného zdrojového snímku na zadanou pozici v kolekci.
            Vhodné rozložení bude automaticky vybráno ze zadaného 
            masteru (vhodné rozložení je rozložení se stejným Typem nebo Názvem jako 
            rozložení zdrojového snímku). Pokud neexistuje vhodné rozložení, 
            rozložení zdrojového snímku bude klonováno (pokud je allowCloneMissingLayout 
            true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout
            false).

### Vrací

Vložený snímek.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index nového snímku. |
| source_slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Snímek ke klonování. |
| dest_master | [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide) | Master snímek pro nový snímek. |
| allow_clone_missing_layout | **bool** | Pokud v zadaném masteru neexistuje vhodné rozložení, bude rozložení <br/><br/>            zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo <br/><br/>            bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud v zadaném masteru neexistuje vhodné rozložení a allowCloneMissingLayout je false. |



### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide)
* třída [`ISlide`](/slides/python-net/cs/aspose.slides/islide)
* třída [`ISlideCollection`](/slides/python-net/cs/aspose.slides/islidecollection)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)