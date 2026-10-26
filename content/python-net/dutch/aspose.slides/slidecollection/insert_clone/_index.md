---
title: insert_clone method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Voegt een kopie van een opgegeven dia toe op de opgegeven positie in de verzameling.

### Retour
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
Een intern register wordt gebruikt om automatisch gekloonde masters bij te houden om het aanmaken van meerdere klonen van dezelfde masterdia te voorkomen.  
Handmatig klonen van masterdia's zal noch worden voorkomen noch geregistreerd.  
Als u meer controle over het kloonproces nodig hebt, gebruikt u  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** of  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** voor het klonen van dia's en  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** voor het klonen van masters.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Voegt een kopie van een opgegeven dia toe op de opgegeven positie in de verzameling.

### Retour
Ingevoegde dia.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Index van de nieuwe dia. |
| source_slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | Dia om te klonen. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide) | Lay-outdia voor de nieuwe dia. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Voegt een kopie van een opgegeven bron-dia toe op de opgegeven positie in de verzameling.  
Het passende lay-out wordt automatisch geselecteerd uit de opgegeven  
master (een passend lay-out is het lay-out met hetzelfde Type of dezelfde Naam als  
het lay-out van de bron-dia). Als er geen passend lay-out bestaat, wordt  
het lay-out van de bron-dia gekloond (als allowCloneMissingLayout  
true is) of wordt PptxEditException gegooid (als allowCloneMissingLayout  
false is).

### Retour
Ingevoegde dia.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | Index van de nieuwe dia. |
| source_slide | [`ISlide`](/slides/python-net/nl/aspose.slides/islide) | Dia om te klonen. |
| dest_master | [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide) | Masterdia voor de nieuwe dia. |
| allow_clone_missing_layout | **bool** | Als er geen passend lay-out is in de opgegeven master, wordt het lay-out van de <br/><br/>            bron-dia gekloond (als allowCloneMissingLayout true is) of <br/><br/>            PptxEditException gegooid (als allowCloneMissingLayout false is). |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Gegooid als er geen passend lay-out is in de opgegeven master en <br/>            allowCloneMissingLayout false is. |



### Zie ook
* klasse [`ILayoutSlide`](/slides/python-net/nl/aspose.slides/ilayoutslide)
* klasse [`IMasterSlide`](/slides/python-net/nl/aspose.slides/imasterslide)
* klasse [`ISlide`](/slides/python-net/nl/aspose.slides/islide)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* klasse [`SlideCollection`](/slides/python-net/nl/aspose.slides/slidecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)