---
title: insert_clone method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Fügt eine Kopie einer angegebenen Folie an einer angegebenen Position der Sammlung ein.

### Rückgabewert

Eingefügte Folie.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Index der neuen Folie. |
| source_slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Folie, die geklont werden soll. |

### Bemerkungen

Beim Klonen einer Folie zwischen verschiedenen Präsentationen kann auch der Master der Folie geklont werden.
Ein internes Register wird verwendet, um automatisch geklonte Master zu verfolgen und die Erstellung mehrerer Klone desselben Master-Folien zu verhindern.
Manuelles Klonen von Master-Folien wird weder verhindert noch registriert.
Wenn Sie mehr Kontrolle über den Klon-Vorgang benötigen, verwenden Sie
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** oder
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** zum Klonen von Folien und
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** zum Klonen von Mastern.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Fügt eine Kopie einer angegebenen Folie an einer angegebenen Position der Sammlung ein.

### Rückgabewert

Eingefügte Folie



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Index der neuen Folie. |
| source_slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Folie, die geklont werden soll. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Layout-Folie für die neue Folie. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Fügt eine Kopie einer angegebenen Quellfolie an einer angegebenen Position der Sammlung ein.
Ein geeignetes Layout wird automatisch aus dem angegebenen Master ausgewählt (ein geeignetes Layout ist das Layout mit dem gleichen Type oder Name wie das Layout der Quellfolie). Wenn kein geeignetes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder es wird eine PptxEditException ausgelöst (wenn allowCloneMissingLayout false ist).

### Rückgabewert

Eingefügte Folie.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Index der neuen Folie. |
| source_slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Folie, die geklont werden soll. |
| dest_master | [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide) | Master-Folie für die neue Folie. |
| allow_clone_missing_layout | **bool** | Wenn im angegebenen Master kein geeignetes Layout vorhanden ist, wird das Layout der <br/><br/>            Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder <br/><br/>            PptxEditException wird ausgelöst (wenn allowCloneMissingLayout false ist). |

### Ausnahmen

| Exception | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Ausgelöst, wenn im angegebenen Master kein geeignetes Layout vorhanden ist und <br/>            allowCloneMissingLayout false ist. |



### Siehe auch
* class [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide)
* class [`ISlide`](/slides/python-net/de/aspose.slides/islide)
* class [`ISlideCollection`](/slides/python-net/de/aspose.slides/islidecollection)
* class [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)