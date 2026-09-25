---
title: get_images method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Returnerar Thumbnail Image-objekt för alla bilder i en presentation.

### Returns

Bitmap objects.



```python
def get_images(self, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Returnerar Thumbnail Bitmap-objekt för angivna bilder i en presentation.

### Returns

Bitmap objects.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| slides | **List[int]** | Array med bildpositioner, med start på 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Returnerar Thumbnail Image-objekt för alla bilder i en presentation med angiven storlek.

### Returns

Bitmap objects.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| image_size | [`Size`](/slides/python-net/sv/aspose.slides/size) | Storlek på bilden som ska skapas. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Returnerar Thumbnail Image-objekt för alla bilder i en presentation med anpassad skalning.

### Returns

Bitmap objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| scale_x | **float** | Värdet med vilket detta Thumbnail skalas i x-axelns riktning. |
| scale_y | **float** | Värdet med vilket detta Thumbnail skalas i y-axelns riktning. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Returnerar Thumbnail Image-objekt för angivna bilder i en presentation med angiven storlek.

### Returns

Bitmap objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| slides | **List[int]** | Array med bildpositioner, med start på 1. |
| image_size | [`Size`](/slides/python-net/sv/aspose.slides/size) | Storlek på bilden som ska skapas. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Returnerar Thumbnail Image-objekt för angivna bilder i en presentation med anpassad skalning.

### Returns

Bitmap objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| slides | **List[int]** | Array med bildpositioner, med start på 1. |
| scale_x | **float** | Värdet med vilket detta Thumbnail skalas i x-axelns riktning. |
| scale_y | **float** | Värdet med vilket detta Thumbnail skalas i y-axelns riktning. |



### Se också
* klass [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)
* klass [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions)
* klass [`Size`](/slides/python-net/sv/aspose.slides/size)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)