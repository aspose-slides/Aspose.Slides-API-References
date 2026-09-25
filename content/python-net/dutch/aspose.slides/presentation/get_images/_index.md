---
title: get_images method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Retourneert Image-objecten voor alle dia's van een presentatie.

### Retour
Image-objecten.



```python
def get_images(self, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Tiff-opties. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Retourneert Thumbnail Image-objecten voor de opgegeven dia's van een presentatie.

### Retour
Image-objecten.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Tiff-opties. |
| slides | **List[int]** | Array met dia-posities, beginnend bij 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie met opgegeven grootte.

### Retour
Image-objecten.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Tiff-opties. |
| image_size | [`Size`](/slides/python-net/nl/aspose.slides/size) | Grootte van de te maken afbeelding. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie met aangepaste schaal.

### Retour
Image-objecten.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Tiff-opties. |
| scale_x | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scale_y | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Retourneert Thumbnail Image-objecten voor de opgegeven dia's van een presentatie met opgegeven grootte.

### Retour
Image-objecten.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Tiff-opties. |
| slides | **List[int]** | Array met dia-posities, beginnend bij 1. |
| image_size | [`Size`](/slides/python-net/nl/aspose.slides/size) | Grootte van de te maken afbeelding. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Retourneert Thumbnail Image-objecten voor de opgegeven dia's van een presentatie met aangepaste schaal.

### Retour
Image-objecten.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Tiff-opties. |
| slides | **List[int]** | Array met dia-posities, beginnend bij 1. |
| scale_x | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scale_y | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |



### Zie ook
* klasse [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions)
* klasse [`Presentation`](/slides/python-net/nl/aspose.slides/presentation)
* klasse [`Size`](/slides/python-net/nl/aspose.slides/size)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)