---
title: get_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Gibt ein Thumbnail Image-Objekt (20 % der Originalgröße) zurück.


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
Gibt ein Thumbnail Image-Objekt mit der angegebenen Größe zurück.

### Rückgabe

Image-Objekt.



```python
def get_image(self, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | Größe des zu erstellenden Bildes. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Gibt ein Thumbnail tiff Bild-Objekt mit den angegebenen Parametern zurück.

### Rückgabe

Image-Objekt.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/de/aspose.slides.export/itiffoptions) | Tiff-Optionen. |

### Ausnahmen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn options.SlideLayoutOption NotesCommentsLayoutingOptions ist und seine Eigenschaft NotesPosition den Wert NotesPositions.BottomFull annimmt. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Gibt ein Thumbnail Image-Objekt zurück.

### Rückgabe

Image-Objekt.



```python
def get_image(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |

### Ausnahmen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn notesCommentsLayouting.NotesPosition den Wert NotesPositions.BottomFull annimmt. |


## get_image(self, scale_x, scale_y) {#float-float}
Gibt ein Thumbnail Image-Objekt mit benutzerdefinierter Skalierung zurück.

### Rückgabe

IImage-Objekt.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | **float** | Der Wert, um den dieses Thumbnail in x-Richtung skaliert wird. |
| scale_y | **float** | Der Wert, um den dieses Thumbnail in y-Richtung skaliert wird. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Gibt ein Thumbnail Image-Objekt mit der angegebenen Größe zurück.

### Rückgabe

Image-Objekt.



```python
def get_image(self, options, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |
| image_size | **aspose.slides.Size** | Größe des zu erstellenden Bildes. |

### Ausnahmen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn options.SlideLayoutOption NotesCommentsLayoutingOptions ist und seine Eigenschaft NotesPosition den Wert NotesPositions.BottomFull annimmt. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Gibt ein Thumbnail Image-Objekt mit benutzerdefinierter Skalierung zurück.

### Rückgabe

Bitmap-Objekte.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions) | Rendering-Optionen. |
| scale_x | **float** | Der Wert, um den dieses Thumbnail in x-Richtung skaliert wird. |
| scale_y | **float** | Der Wert, um den dieses Thumbnail in y-Richtung skaliert wird. |

### Ausnahmen

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn notesCommentsLayouting.NotesPosition den Wert NotesPositions.BottomFull annimmt. |



### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Klasse [`IRenderingOptions`](/slides/python-net/de/aspose.slides.export/irenderingoptions)
* Klasse [`ITiffOptions`](/slides/python-net/de/aspose.slides.export/itiffoptions)
* Klasse [`Slide`](/slides/python-net/de/aspose.slides/slide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)