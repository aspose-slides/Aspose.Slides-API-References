---
title: insert_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Infogar en kopia av en specificerad bild på angiven position i samlingen.

### Returnerar

Infogad bild.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Index för den nya bilden. |
| source_slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Bild att klona. |

### Anmärkningar

När en bild klonas mellan olika presentationer kan bildens master också klonas.
            Intern register används för att spåra automatiskt klonade master-bilder för att förhindra att flera kloner av samma master-bild skapas.
            Manuell kloning av master-bilder kommer varken att förhindras eller registreras.
            Om du behöver mer kontroll över kloningsprocessen, använd
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** eller
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** för att klona bilder och
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** för att klona master-bilder.



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Infogar en kopia av en specificerad bild på angiven position i samlingen.

### Returnerar

Infogad bild.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Index för den nya bilden. |
| source_slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Bild att klona. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Layout-bild för den nya bilden. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Infogar en kopia av en specificerad källbild på angiven position i samlingen.
            Ett lämpligt layout kommer väljas automatiskt från den angivna 
            master-bilden (ett lämpligt layout är det layout som har samma Typ eller Namn som 
            layouten för källbilden). Om det inte finns något lämpligt layout så
            klonas layouten från källbilden (om allowCloneMissingLayout 
            är sann) eller så kastas PptxEditException (om allowCloneMissingLayout
            är falskt).

### Returnerar

Infogad bild.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Index för den nya bilden. |
| source_slide | [`ISlide`](/slides/python-net/sv/aspose.slides/islide) | Bild att klona. |
| dest_master | [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide) | Master-bild för den nya bilden. |
| allow_clone_missing_layout | **bool** | Om det inte finns ett lämpligt layout i angiven master så klonas layouten från <br/><br/>            källbilden (om allowCloneMissingLayout är sann) eller <br/><br/>            PptxEditException kastas (om allowCloneMissingLayout är falskt). |

### Undantag

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om det inte finns ett lämpligt layout i angiven master och <br/>            allowCloneMissingLayout är falskt. |



### Se även
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide)
* klass [`ISlide`](/slides/python-net/sv/aspose.slides/islide)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* klass [`SlideCollection`](/slides/python-net/sv/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)