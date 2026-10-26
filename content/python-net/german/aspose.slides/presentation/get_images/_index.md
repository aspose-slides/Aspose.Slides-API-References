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

### Rückgabe

Image-Objekte.



```python
def get_images(self, options):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Gibt Thumbnail-Image-Objekte für angegebene Folien einer Präsentation zurück.

### Rückgabe

Image-Objekte.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit angegebenen Abmessungen zurück.

### Rückgabe

Image-Objekte.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |
| image_size | [`Size`](/slides/python-net/de/aspose.slides/size) | Größe des zu erstellenden Bildes. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

### Rückgabe

Image-Objekte.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |
| scale_x | **float** | Der Wert, um den diese Thumbnail in x-Achsen-Richtung skaliert wird. |
| scale_y | **float** | Der Wert, um den diese Thumbnail in y-Achsen-Richtung skaliert wird. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Gibt Thumbnail-Image-Objekte für angegebene Folien einer Präsentation mit angegebenen Abmessungen zurück.

### Rückgabe

Image-Objekte.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| image_size | [`Size`](/slides/python-net/de/aspose.slides/size) | Größe des zu erstellenden Bildes. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Gibt Thumbnail-Image-Objekte für angegebene Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

### Rückgabe

Image-Objekte.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Tiff-Optionen. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| scale_x | **float** | Der Wert, um den diese Thumbnail in x-Achsen-Richtung skaliert wird. |
| scale_y | **float** | Der Wert, um den diese Thumbnail in y-Achsen-Richtung skaliert wird. |



### Siehe auch
* Klasse [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions)
* Klasse [`Presentation`](/slides/python-net/de/aspose.slides/presentation)
* Klasse [`Size`](/slides/python-net/de/aspose.slides/size)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)