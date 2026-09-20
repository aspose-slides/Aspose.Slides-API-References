---
title: insert_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Infogar en kopia av en specificerad bild på en specificerad position i samlingen.

### Returnerar

Infogad bild.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Index för ny bild. |
| source_slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Bild att klona. |

### Anmärkningar

När en bild klonas mellan olika presentationer kan bildens master också klonas.
Internt register används för att spåra automatiskt klonade masterbilder för att förhindra skapandet av flera kopior av samma masterbild.
Manuell kloning av masterbilder kommer varken att förhindras eller registreras.
Om du behöver mer kontroll över kloningsprocessen, använd
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** eller
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** för att klona bilder och
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** för att klona masterbilder.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Infogar en kopia av en specificerad bild på en specificerad position i samlingen.

### Returnerar

Infogad bild.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Index för ny bild. |
| source_slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Bild att klona. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Layoutbild för den nya bilden. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Infogar en kopia av en specificerad källbild på en specificerad position i samlingen.
            Ett lämpligt layout kommer att väljas automatiskt från den specificerade 
            master (ett lämpligt layout är den layout som har samma Typ eller Namn som 
            layouten för källbilden). Om det inte finns någon lämplig layout kommer
            layouten för källbilden att klonas (om allowCloneMissingLayout 
            är sant) eller så kommer PptxEditException att kastas (om allowCloneMissingLayout
            är falskt).

### Returnerar

Infogad bild.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Index för ny bild. |
| source_slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Bild att klona. |
| dest_master | [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide) | Masterbild för den nya bilden. |
| allow_clone_missing_layout | **bool** | Om det inte finns någon lämplig layout i den specificerade master så kommer layouten för <br/><br/>            källbilden att klonas (om allowCloneMissingLayout är sant) eller <br/><br/>            PptxEditException kommer att kastas (om allowCloneMissingLayout är falskt). |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om det inte finns någon lämplig layout i den specificerade master och <br/>            allowCloneMissingLayout är falskt. |



### Se även
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide)
* klass [`ISlide`](/slides/python-net/sv/aspose.slides/islide)
* klass [`ISlideCollection`](/slides/python-net/sv/aspose.slides/islidecollection)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)