---
title: insert_clone method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Fügt eine Kopie einer angegebenen Folie an der angegebenen Position der Sammlung ein.

### Rückgabewert

Einfügte Folie.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Index der neuen Folie. |
| source_slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Folie zum Klonen. |

### Hinweise

Beim Klonen einer Folie zwischen verschiedenen Präsentationen kann auch das Master der Folie geklont werden.  
Internes Register wird verwendet, um automatisch geklonte Master zu verfolgen und die Erstellung mehrerer Klone derselben Master-Folie zu verhindern.  
Manuelles Klonen von Master-Folien wird weder verhindert noch registriert.  
Wenn Sie mehr Kontrolle über den Klonvorgang benötigen, verwenden Sie  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** oder  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** für das Klonen von Folien und  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** für das Klonen von Mastern.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Fügt eine Kopie einer angegebenen Folie an der angegebenen Position der Sammlung ein.

### Rückgabewert

Einfügte Folie.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Index der neuen Folie. |
| source_slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Folie zum Klonen. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Layout-Folie für die neue Folie. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Fügt eine Kopie einer angegebenen Quellfolie an der angegebenen Position der Sammlung ein.  
Ein passendes Layout wird automatisch aus dem angegebenen Master ausgewählt (ein passendes Layout ist das Layout mit demselben Typ oder Namen wie das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout wahr ist) oder es wird eine PptxEditException ausgelöst (wenn allowCloneMissingLayout falsch ist).

### Rückgabewert

Einfügte Folie.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Index der neuen Folie. |
| source_slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Folie zum Klonen. |
| dest_master | [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide) | Master-Folie für die neue Folie. |
| allow_clone_missing_layout | **bool** | Falls im angegebenen Master kein passendes Layout vorhanden ist, wird das Layout der <br/><br/>            Quellfolie geklont (wenn allowCloneMissingLayout wahr ist) oder <br/><br/>            PptxEditException wird ausgelöst (wenn allowCloneMissingLayout falsch ist). |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Ausgelöst, wenn im angegebenen Master kein passendes Layout vorhanden ist und <br/>            allowCloneMissingLayout falsch ist. |



### Siehe auch
* class [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide)
* class [`ISlide`](/slides/python-net/de/aspose.slides/islide)
* class [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* class [`SlideCollection`](/slides/python-net/de/aspose.slides/slidecollection)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)