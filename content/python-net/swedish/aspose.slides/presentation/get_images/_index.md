---
title: get_images method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Returnerar Image objects för alla bilder i en presentation.

### Returnerar

Image objects.



```python
def get_images(self, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Returnerar Thumbnail Image objects för angivna bilder i en presentation.

### Returnerar

Image objects.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |
| slides | **List[int]** | Array med bildpositioner, med start från 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Returnerar Thumbnail Image objects för alla bilder i en presentation med angiven storlek.

### Returnerar

Image objects.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |
| image_size | **aspose.slides.Size** | Storlek på bilden som ska skapas. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Returnerar Thumbnail Image objects för alla bilder i en presentation med anpassad skalning.

### Returnerar

Image objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |
| scale_x | **float** | Värdet som används för att skala denna Thumbnail i x-axelns riktning. |
| scale_y | **float** | Värdet som används för att skala denna Thumbnail i y-axelns riktning. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Returnerar Thumbnail Image objects för angivna bilder i en presentation med angiven storlek.

### Returnerar

Image objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |
| slides | **List[int]** | Array med bildpositioner, med start från 1. |
| image_size | **aspose.slides.Size** | Storlek på bilden som ska skapas. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Returnerar Thumbnail Image objects för angivna bilder i en presentation med anpassad skalning.

### Returnerar

Image objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Tiff-alternativ. |
| slides | **List[int]** | Array med bildpositioner, med start från 1. |
| scale_x | **float** | Värdet som används för att skala denna Thumbnail i x-axelns riktning. |
| scale_y | **float** | Värdet som används för att skala denna Thumbnail i y-axelns riktning. |



### Se även
* klass [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions)
* klass [`Presentation`](/slides/python-net/sv/aspose.slides/presentation)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)