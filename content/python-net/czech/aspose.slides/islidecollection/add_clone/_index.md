---
title: add_clone method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Přidá kopii určeného snímku na konec kolekce.

### Návratová hodnota

Nový snímek.



```python
def add_clone(self, source_slide):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Snímek k naklonování. |

### Poznámky

Při klonování snímku mezi různými prezentacemi může být klonován také master snímku.  
Interní registr se používá ke sledování automaticky klonovaných masterů, aby se zabránilo vytvoření  
více klonů stejného master snímku.  
Manuální klonování master snímků nebude ani zabráněno, ani zaznamenáno.  
Pokud potřebujete větší kontrolu nad procesem klonování, použijte  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** nebo  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** pro klonování snímků,  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** nebo  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** pro klonování rozvržení a  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** pro klonování masterů.


## add_clone(self, source_slide, section) {#islide-isection}
Přidá kopii určeného snímku na konec určené sekce.

### Návratová hodnota

Nový snímek.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Snímek k naklonování. |
| section | [`ISection`](/slides/python-net/cs/aspose.slides/isection) | Sekce pro nový snímek. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Přidá kopii určeného snímku na konec kolekce.

### Návratová hodnota

Nový snímek.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Snímek k naklonování. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Rozvržení snímku pro nový snímek. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Přidá kopii určeného zdrojového snímku na konec kolekce. Vhodné rozvržení bude automaticky vybráno ze zadaného masteru (vhodné rozvržení je rozvržení se stejným Type nebo Name jako rozvržení zdrojového snímku). Pokud neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku zkopírováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false).

### Návratová hodnota

Nový snímek.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/cs/aspose.slides/islide) | Snímek k naklonování. |
| dest_master | [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide) | Master snímek pro nový snímek. |
| allow_clone_missing_layout | **bool** | Pokud neexistuje vhodné rozvržení ve zvoleném masteru, bude rozvržení zdrojového snímku zkopírováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud neexistuje vhodné rozvržení ve zvoleném masteru a <br/>            allowCloneMissingLayout je false. |



### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide)
* třída [`ISection`](/slides/python-net/cs/aspose.slides/isection)
* třída [`ISlide`](/slides/python-net/cs/aspose.slides/islide)
* třída [`ISlideCollection`](/slides/python-net/cs/aspose.slides/islidecollection)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)