---
title: get_images method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation zurück.

### Rückgabe
Bitmap-Objekte.

```python
def get_images(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |

## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Gibt Thumbnail-Bitmap-Objekte für die angegebenen Folien einer Präsentation zurück.

### Rückgabe
Bitmap-Objekte.

```python
def get_images(self, options, slides):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |

## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit bestimmter Größe zurück.

### Rückgabe
Bitmap-Objekte.

```python
def get_images(self, options, image_size):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |
| image_size | **aspose.slides.Size** | Größe des zu erstellenden Bildes. |

## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

### Rückgabe
Bitmap-Objekte.

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |
| scale_x | **float** | Der Wert, um den dieses Thumbnail in x-Richtung skaliert wird. |
| scale_y | **float** | Der Wert, um den dieses Thumbnail in y-Richtung skaliert wird. |

## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Gibt Thumbnail-Image-Objekte für die angegebenen Folien einer Präsentation mit bestimmter Größe zurück.

### Rückgabe
Bitmap-Objekte.

```python
def get_images(self, options, slides, image_size):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| image_size | **aspose.slides.Size** | Größe des zu erstellenden Bildes. |

## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Gibt Thumbnail-Image-Objekte für die angegebenen Folien einer Präsentation mit benutzerdefinierter Skalierung zurück.

### Rückgabe
Bitmap-Objekte.

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |
| slides | **List[int]** | Array mit Folienpositionen, beginnend bei 1. |
| scale_x | **float** | Der Wert, um den dieses Thumbnail in x-Richtung skaliert wird. |
| scale_y | **float** | Der Wert, um den dieses Thumbnail in y-Richtung skaliert wird. |

### Siehe auch
* Klasse [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)
* Klasse [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)