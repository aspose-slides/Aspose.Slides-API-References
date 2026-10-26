---
title: add_clone method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Voegt een kopie van een opgegeven dia toe aan het einde van de collectie.

### Retour

Nieuwe dia.



```python
def add_clone(self, source_slide):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | Dia om te klonen. |

### Opmerkingen

Bij het klonen van een dia tussen verschillende presentaties kan de master van de dia ook worden gekloond.  
Het interne register wordt gebruikt om automatisch gekloonde masters bij te houden om het maken van meerdere klonen van dezelfde masterdia te voorkomen.  
Handmatig klonen van masterdia's zal noch worden voorkomen noch geregistreerd.  
Als u meer controle over het kloonproces nodig heeft, gebruik dan  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** of  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** voor het klonen van dia's,  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** of  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** voor het klonen van lay-outs en  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** voor het klonen van masters.


## add_clone(self, source_slide, section) {#islide-isection}
Voegt een kopie van een opgegeven dia toe aan het einde van de opgegeven sectie.

### Retour

Nieuwe dia.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | Dia om te klonen. |
| section | [`ISection`](/slides/python-net/nl/aspose.slides/isection) | Sectie voor een nieuwe dia. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Voegt een kopie van een opgegeven dia toe aan het einde van de collectie.

### Retour

Nieuwe dia.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | Dia om te klonen. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | Lay-outdia voor een nieuwe dia. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Voegt een kopie van een opgegeven bron-dia toe aan het einde van de collectie.  
Een geschikte lay-out wordt automatisch geselecteerd uit de opgegeven master (een geschikte lay-out is de lay-out met hetzelfde Type of dezelfde Name als de lay-out van de bron-dia). Als er geen geschikte lay-out is, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt PptxEditException gegooid (als allowCloneMissingLayout false is).

### Retour

Nieuwe dia.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | Dia om te klonen. |
| dest_master | [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide) | Masterdia voor een nieuwe dia. |
| allow_clone_missing_layout | **bool** | Als er geen geschikte lay-out in de opgegeven master is, wordt de lay-out van de <br/><br/>            bron-dia gekloond (als allowCloneMissingLayout true is) of <br/><br/>            PptxEditException gegooid (als allowCloneMissingLayout false is). |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Gegooid als er geen geschikte lay-out in de opgegeven master is en <br/>            allowCloneMissingLayout false is. |



### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide)
* klasse [`ISection`](/slides/python-net/nl/aspose.slides/isection)
* klasse [`ISlide`](/slides/python-net/nl/aspose.slides/islide)
* klasse [`ISlideCollection`](/slides/python-net/nl/aspose.slides/islidecollection)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)