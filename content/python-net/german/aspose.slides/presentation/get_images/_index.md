---
title: get_images method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Gibt Image-Objekte für alle Folien einer Präsentation zurück.

### Rückgabewert

Image objects.



```python
def get_images(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Gibt Thumbnail-Image-Objekte für die angegebenen Folien einer Präsentation zurück.

### Rückgabewert

Image objects.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit angegebener Größe zurück.

### Rückgabewert

Image objects.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |
| image_size | **aspose.slides.Size** | Größe des zu erstellenden Bildes. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

### Rückgabewert

Image objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |
| scale_x | **float** | Der Wert, um den dieses Thumbnail in x-Achsenrichtung skaliert wird. |
| scale_y | **float** | Der Wert, um den dieses Thumbnail in y-Achsenrichtung skaliert wird. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Gibt Thumbnail-Image-Objekte für die angegebenen Folien einer Präsentation mit angegebener Größe zurück.

### Rückgabewert

Image objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| image_size | **aspose.slides.Size** | Größe des zu erstellenden Bildes. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Gibt Thumbnail-Image-Objekte für die angegebenen Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

### Rückgabewert

Image objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| scale_x | **float** | Der Wert, um den dieses Thumbnail in x-Achsenrichtung skaliert wird. |
| scale_y | **float** | Der Wert, um den dieses Thumbnail in y-Achsenrichtung skaliert wird. |



### Siehe auch
* Klasse [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions)
* Klasse [`Presentation`](/slides/python-net/de/aspose.slides/presentation)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)