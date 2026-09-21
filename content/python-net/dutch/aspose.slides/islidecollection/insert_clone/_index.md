---
title: insert_clone method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Voegt een kopie van een opgegeven dia in op een gespecificeerde positie in de collectie.

### Retourwaarde

Ingevoegde dia.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Index van de nieuwe dia. |
| source_slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | Dia om te klonen. |

### Opmerkingen

Bij het klonen van een dia tussen verschillende presentaties kan de master van de dia ook worden gekloond.
Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.
Manual cloning of master slides will be neither prevented nor registered.
If you need more control over cloning process use
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** or
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides and
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Voegt een kopie van een opgegeven dia in op een gespecificeerde positie in de collectie.

### Retourwaarde

Ingevoegde dia.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Index van de nieuwe dia. |
| source_slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | Dia om te klonen. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | Layoutdia voor een nieuwe dia. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Voegt een kopie van een opgegeven bron-dia in op een gespecificeerde positie in de collectie.
Appropriate layout will be selected automatically from the specified 
master (appropriate layout is the layout with the same Type or Name as 
of layout of the source slide). If there is no appropriate layout then
layout of the source slide will be cloned (if allowCloneMissingLayout 
is true) or PptxEditException will be thrown (if allowCloneMissingLayout
is false).

### Retourwaarde

Ingevoegde dia.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Index van de nieuwe dia. |
| source_slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | Dia om te klonen. |
| dest_master | [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide) | Masterdia voor een nieuwe dia. |
| allow_clone_missing_layout | **bool** | Als er geen geschikt layout is in de opgegeven master dan layout van de <br/><br/>            source slide zal worden gekloond (if allowCloneMissingLayout is true) of <br/><br/>            PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Thrown if there is no appropriate layout in specified master and <br/>            allowCloneMissingLayout is false. |



### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide)
* klasse [`ISlide`](/slides/python-net/nl/aspose.slides/islide)
* klasse [`ISlideCollection`](/slides/python-net/nl/aspose.slides/islidecollection)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)