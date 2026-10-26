---
title: insert_clone method
second_title: Aspose.Slides pro Python pomocí .NET API
description: 
type: docs
url: /cs/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Vloží kopii určeného snímku na zadanou pozici ve sbírce.

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

Při klonování snímku mezi různými prezentacemi může být klonován také hlavní snímek. Interní registr je používán ke sledování automaticky klonovaných hlavních snímků, aby se zabránilo vytvoření více kopií stejného hlavního snímku. Manuální klonování hlavních snímků není ani zakázáno, ani registrováno. Pokud potřebujete větší kontrolu nad procesem klonování, použijte **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** nebo **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** pro klonování snímků a **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** pro klonování hlavních snímků.

## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Vloží kopii určeného snímku na zadanou pozici ve sbírce.

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
Vloží kopii určeného zdrojového snímku na zadanou pozici ve sbírce.
Vhodné rozložení bude automaticky vybráno ze zadaného
hlavního snímku (vhodné rozložení je rozložení se stejným Typem nebo názvem jako
rozložení zdrojového snímku). Pokud neexistuje vhodné rozložení,
rozložení zdrojového snímku bude klonováno (pokud je allowCloneMissingLayout
pravda) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout
nepravda).

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
| dest_master | [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide) | Hlavní snímek pro nový snímek. |
| allow_clone_missing_layout | **bool** | Pokud neexistuje vhodné rozložení ve zvoleném hlavním snímku, bude rozložení <br/><br/>            zdrojového snímku klonováno (pokud je allowCloneMissingLayout pravda) nebo <br/><br/>            bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout nepravda). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud neexistuje vhodné rozložení ve zvoleném hlavním snímku a <br/>            allowCloneMissingLayout je nepravda. |

### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide)
* třída [`ISlide`](/slides/python-net/cs/aspose.slides/islide)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* třída [`SlideCollection`](/slides/python-net/cs/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)