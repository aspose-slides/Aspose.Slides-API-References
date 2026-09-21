---
title: get_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Retourneert een Thumbnail Image object (20% van de werkelijke grootte).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
Retourneert een Thumbnail Image object met opgegeven grootte.

### Retour

Image-object.



```python
def get_image(self, image_size):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | Grootte van de afbeelding die moet worden aangemaakt. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Retourneert een Thumbnail tiff image object met opgegeven parameters.

### Retour

Image-object.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/nl/aspose.slides.export/itiffoptions) | Tiff-opties. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wordt gegooid wanneer options.SlideLayoutOption NotesCommentsLayoutingOptions is en zijn eigenschap NotesPosition de waarde NotesPositions.BottomFull heeft. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Retourneert een Thumbnail Image object.

### Retour

Image-object.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering-opties. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wordt gegooid wanneer notesCommentsLayouting.NotesPosition de waarde NotesPositions.BottomFull heeft. |


## get_image(self, scale_x, scale_y) {#float-float}
Retourneert een Thumbnail Image object met aangepaste schaal.

### Retour

IImage-object.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| scale_x | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scale_y | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Retourneert een Thumbnail Image object met opgegeven grootte.

### Retour

Image-object.



```python
def get_image(self, options, image_size):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering-opties. |
| image_size | **aspose.slides.Size** | Grootte van de afbeelding die moet worden aangemaakt. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wordt gegooid wanneer options.SlideLayoutOption NotesCommentsLayoutingOptions is en zijn eigenschap NotesPosition de waarde NotesPositions.BottomFull heeft. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Retourneert een Thumbnail Image object met aangepaste schaal.

### Retour

Bitmap-objecten.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions) | Rendering-opties. |
| scale_x | **float** | De waarde waarmee deze Thumbnail in de x-as wordt geschaald. |
| scale_y | **float** | De waarde waarmee deze Thumbnail in de y-as wordt geschaald. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wordt gegooid wanneer notesCommentsLayouting.NotesPosition de waarde NotesPositions.BottomFull heeft. |



### Zie ook
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* klasse [`IRenderingOptions`](/slides/python-net/nl/aspose.slides.export/irenderingoptions)
* klasse [`ITiffOptions`](/slides/python-net/nl/aspose.slides.export/itiffoptions)
* klasse [`Slide`](/slides/python-net/nl/aspose.slides/slide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)