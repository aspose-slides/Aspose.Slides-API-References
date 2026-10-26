---
title: add_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Lägger till en kopia av en specificerad bild i slutet av samlingen.

### Returnvärde

Ny bild.



```python
def add_clone(self, source_slide):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Bild att klona. |

### Anmärkningar

När du klonar en bild mellan olika presentationer kan bildens master också klonas.
Det interna registret används för att spåra automatiskt klonade masters för att förhindra skapandet av flera kloner av samma master-bild.
Manuell kloning av master-bilder kommer varken att förhindras eller registreras.
Om du behöver mer kontroll över kloningsprocessen använder du
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** eller
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** för att klona bilder,
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** eller
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** för att klona layouter och
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** för att klona masters.


## add_clone(self, source_slide, section) {#islide-isection}
Lägger till en kopia av en specificerad bild i slutet av det angivna avsnittet.

### Returnvärde

Ny bild.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Bild att klona. |
| section | [`ISection`](/slides/python-net/sv/aspose.slides/isection) | Avsnitt för en ny bild. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Lägger till en kopia av en specificerad bild i slutet av samlingen.

### Returnvärde

Ny bild.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Bild att klona. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Layout-bild för en ny bild. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Lägger till en kopia av en specificerad källbild i slutet av samlingen.
Lämplig layout kommer att väljas automatiskt från den angivna
mastern (lämplig layout är den layout som har samma Typ eller Namn som
layouten för källbilden). Om det inte finns någon lämplig layout kommer
layouten för källbilden att klonas (om allowCloneMissingLayout
är sant) eller så kommer PptxEditException att kastas (om allowCloneMissingLayout
är falskt).

### Returnvärde

Ny bild.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Bild att klona. |
| dest_master | [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide) | Master-bild för en ny bild. |
| allow_clone_missing_layout | **bool** | Om det inte finns någon lämplig layout i den angivna master kommer layouten för <br/><br/>            källbilden att klonas (om allowCloneMissingLayout är sant) eller <br/><br/>            PptxEditException kommer att kastas (om allowCloneMissingLayout är falskt). |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om det inte finns någon lämplig layout i den angivna master och <br/>            allowCloneMissingLayout är falskt. |



### Se även
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide)
* klass [`ISection`](/slides/python-net/sv/aspose.slides/isection)
* klass [`ISlide`](/slides/python-net/sv/aspose.slides/islide)
* klass [`ISlideCollection`](/slides/python-net/sv/aspose.slides/islidecollection)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)