---
title: get_images method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Returnerar Image-objekt för alla bildspel i en presentation.

### Returnerar

Image-objekt.



```python
def get_images(self, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Returnerar Thumbnail Image-objekt för angivna bildspel i en presentation.

### Returnerar

Image-objekt.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |
| slides | **List[int]** | Array med bildpositioner, med början från 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Returnerar Thumbnail Image-objekt för alla bildspel i en presentation med angiven storlek.

### Returnerar

Image-objekt.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |
| image_size | [`Size`](/slides/python-net/sv/aspose.slides/size) | Storlek på bilden som ska skapas. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Returnerar Thumbnail Image-objekt för alla bildspel i en presentation med anpassad skalning.

### Returnerar

Image-objekt.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |
| scale_x | **float** | Värdet med vilket denna miniatyr ska skalas i x-axelns riktning. |
| scale_y | **float** | Värdet med vilket denna miniatyr ska skalas i y-axelns riktning. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Returnerar Thumbnail Image-objekt för angivna bildspel i en presentation med angiven storlek.

### Returnerar

Image-objekt.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |
| slides | **List[int]** | Array med bildpositioner, med början från 1. |
| image_size | [`Size`](/slides/python-net/sv/aspose.slides/size) | Storlek på bilden som ska skapas. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Returnerar Thumbnail Image-objekt för angivna bildspel i en presentation med anpassad skalning.

### Returnerar

Image-objekt.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |
| slides | **List[int]** | Array med bildpositioner, med början från 1. |
| scale_x | **float** | Värdet med vilket denna miniatyr ska skalas i x-axelns riktning. |
| scale_y | **float** | Värdet med vilket denna miniatyr ska skalas i y-axelns riktning. |



### Se även
* klass [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions)
* klass [`Presentation`](/slides/python-net/sv/aspose.slides/presentation)
* klass [`Size`](/slides/python-net/sv/aspose.slides/size)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)