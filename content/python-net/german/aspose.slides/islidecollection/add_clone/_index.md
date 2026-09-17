---
title: add_clone method
second_title: Aspose.Slides für Python via .NET API Referenz
description: 
type: docs
url: /de/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu.

### Rückgabewert

Neue Folie.



```python
def add_clone(self, source_slide):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Folie zum Klonen. |

### Bemerkungen

Beim Klonen einer Folie zwischen verschiedenen Präsentationen kann auch der Master der Folie geklont werden.
Das interne Register wird verwendet, um automatisch geklonte Master zu verfolgen und die Erstellung mehrerer Klone desselben Master-Slides zu verhindern.
Das manuelle Klonen von Master-Slides wird weder verhindert noch registriert.
Wenn Sie mehr Kontrolle über den Klonvorgang benötigen, verwenden Sie
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** oder
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** zum Klonen von Folien,
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** oder
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** zum Klonen von Layouts und
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** zum Klonen von Mastern.


## add_clone(self, source_slide, section) {#islide-isection}
Fügt eine Kopie einer angegebenen Folie am Ende des angegebenen Abschnitts hinzu.

### Rückgabewert

Neue Folie.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Folie zum Klonen. |
| section | [`ISection`](/slides/python-net/de/aspose.slides/isection) | Abschnitt für eine neue Folie. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu.

### Rückgabewert

Neue Folie.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Folie zum Klonen. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Layout-Slide für eine neue Folie. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Fügt eine Kopie einer angegebenen Quellfolie am Ende der Sammlung hinzu.
Das passende Layout wird automatisch aus dem angegebenen master ausgewählt (ein passendes Layout ist das Layout mit dem gleichen Type oder Name wie das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder PptxEditException wird ausgelöst (wenn allowCloneMissingLayout false ist).

### Rückgabewert

Neue Folie.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Folie zum Klonen. |
| dest_master | [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide) | Master-Slide für eine neue Folie. |
| allow_clone_missing_layout | **bool** | Wenn kein passendes Layout im angegebenen master vorhanden ist, wird das Layout der <br/><br/>            source slide geklont (wenn allowCloneMissingLayout true ist) oder <br/><br/>            PptxEditException wird ausgelöst (wenn allowCloneMissingLayout false ist). |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Ausgelöst, wenn kein passendes Layout im angegebenen master vorhanden ist und <br/>            allowCloneMissingLayout false ist. |



### Siehe auch
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide)
* Klasse [`ISection`](/slides/python-net/de/aspose.slides/isection)
* Klasse [`ISlide`](/slides/python-net/de/aspose.slides/islide)
* Klasse [`ISlideCollection`](/slides/python-net/de/aspose.slides/islidecollection)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)