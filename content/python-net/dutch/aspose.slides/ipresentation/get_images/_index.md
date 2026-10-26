---
title: get_images method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie.

### Retour

Bitmap-objecten.



```python
def get_images(self, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering options. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Retourneert Thumbnail Bitmap-objecten voor opgegeven dia's van een presentatie.

### Retour

Bitmap-objecten.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array met dia-posities, beginnend bij 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie met opgegeven grootte.

### Retour

Bitmap-objecten.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering options. |
| image_size | [`Size`](/slides/python-net/nl/aspose.slides/size) | Grootte van de afbeelding die moet worden gemaakt. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Retourneert Thumbnail Image-objecten voor alle dia's van een presentatie met aangepaste schaal.

### Retour

Bitmap-objecten.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering options. |
| scale_x | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scale_y | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Retourneert Thumbnail Image-objecten voor opgegeven dia's van een presentatie met opgegeven grootte.

### Retour

Bitmap-objecten.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array met dia-posities, beginnend bij 1. |
| image_size | [`Size`](/slides/python-net/nl/aspose.slides/size) | Grootte van de afbeelding die moet worden gemaakt. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Retourneert Thumbnail Image-objecten voor opgegeven dia's van een presentatie met aangepaste schaal.

### Retour

Bitmap-objecten.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array met dia-posities, beginnend bij 1. |
| scale_x | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scale_y | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |



### Zie ook
* klasse [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)
* klasse [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions)
* klasse [`Size`](/slides/python-net/nl/aspose.slides/size)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)