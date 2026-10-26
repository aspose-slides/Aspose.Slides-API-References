---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Gibt ein Thumbnail Image Objekt zurück (20 % der Originalgröße).


```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposeslidessize}
Gibt ein Thumbnail Image Objekt mit angegebener Größe zurück.

### Rückgabewert

Image Objekt.



```python
def get_image(self, image_size):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/de/aspose.slides/size) | Größe des zu erstellenden Bildes. |

## get_image(self, options) {#asposeslidesexportitiffoptions}
Gibt ein Thumbnail tiff Image Objekt mit angegebenen Parametern zurück.

### Rückgabewert

Image Objekt.



```python
def get_image(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/de/aspose.slides.export/itiffoptions) | Tiff-Optionen. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn options.SlideLayoutOption NotesCommentsLayoutingOptions ist und dessen Eigenschaft NotesPosition den Wert NotesPositions.BottomFull annimmt. |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
Gibt ein Thumbnail Image Objekt zurück.

### Rückgabewert

Image Objekt.



```python
def get_image(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn notesCommentsLayouting.NotesPosition den Wert NotesPositions.BottomFull annimmt. |

## get_image(self, scale_x, scale_y) {#float-float}
Gibt ein Thumbnail Image Objekt mit benutzerdefinierter Skalierung zurück.

### Rückgabewert

IImage Objekt.



```python
def get_image(self, scale_x, scale_y):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scale_x | **float** | Der Wert, um den dieses Thumbnail in x-Achsenrichtung skaliert wird. |
| scale_y | **float** | Der Wert, um den dieses Thumbnail in y-Achsenrichtung skaliert wird. |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Gibt ein Thumbnail Image Objekt mit angegebener Größe zurück.

### Rückgabewert

Image Objekt.



```python
def get_image(self, options, image_size):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |
| image_size | [`Size`](/slides/python-net/de/aspose.slides/size) | Größe des zu erstellenden Bildes. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn options.SlideLayoutOption NotesCommentsLayoutingOptions ist und dessen Eigenschaft NotesPosition den Wert NotesPositions.BottomFull annimmt. |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Gibt ein Thumbnail Image Objekt mit benutzerdefinierter Skalierung zurück.

### Rückgabewert

Bitmap-Objekte.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |
| scale_x | **float** | Der Wert, um den dieses Thumbnail in x-Achsenrichtung skaliert wird. |
| scale_y | **float** | Der Wert, um den dieses Thumbnail in y-Achsenrichtung skaliert wird. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn notesCommentsLayouting.NotesPosition den Wert NotesPositions.BottomFull annimmt. |

### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Klasse [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions)
* Klasse [`ITiffOptions`](/slides/python-net/de/aspose.slides.export/itiffoptions)
* Klasse [`Slide`](/slides/python-net/de/aspose.slides/slide)
* Klasse [`Size`](/slides/python-net/de/aspose.slides/size)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)