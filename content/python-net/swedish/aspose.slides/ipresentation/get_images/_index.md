---
title: get_images method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Returnerar en Thumbnail Image-objekt för alla bildspel i en presentation.

### Returnerar

Bitmap-objekt.



```python
def get_images(self, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Returnerar en Thumbnail Bitmap-objekt för angivna bildspel i en presentation.

### Returnerar

Bitmap-objekt.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| slides | **List[int]** | Array med bildspelspositioner, med början från 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Returnerar en Thumbnail Image-objekt för alla bildspel i en presentation med angiven storlek.

### Returnerar

Bitmap-objekt.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| image_size | **aspose.slides.Size** | Storlek på bilden som ska skapas. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Returnerar en Thumbnail Image-objekt för alla bildspel i en presentation med anpassad skalning.

### Returnerar

Bitmap-objekt.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| scale_x | **float** | Värdet som används för att skala denna Thumbnail i x-axelns riktning. |
| scale_y | **float** | Värdet som används för att skala denna Thumbnail i y-axelns riktning. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Returnerar en Thumbnail Image-objekt för angivna bildspel i en presentation med angiven storlek.

### Returnerar

Bitmap-objekt.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| slides | **List[int]** | Array med bildspelspositioner, med början från 1. |
| image_size | **aspose.slides.Size** | Storlek på bilden som ska skapas. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Returnerar en Thumbnail Image-objekt för angivna bildspel i en presentation med anpassad skalning.

### Returnerar

Bitmap-objekt.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| slides | **List[int]** | Array med bildspelspositioner, med början från 1. |
| scale_x | **float** | Värdet som används för att skala denna Thumbnail i x-axelns riktning. |
| scale_y | **float** | Värdet som används för att skala denna Thumbnail i y-axelns riktning. |



### Se även
* klass [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)
* klass [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)