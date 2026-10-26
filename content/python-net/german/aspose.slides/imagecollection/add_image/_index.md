---
title: add_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
Fügt eine Kopie eines Bildes aus einer anderen Präsentation hinzu.

### Rückgabe

Hinzugefügtes Bild.



```python
def add_image(self, image_source):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) | Quellbild. |


## add_image(self, image) {#iimage}
Fügt ein Bild zu einer Präsentation hinzu.

### Rückgabe

Hinzugefügtes Bild.



```python
def add_image(self, image):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/de/aspose.slides/iimage) | Hinzuzufügendes Bild. |

### Hinweise

Diese Methode konvertiert WMF/EMF-Metadateien in ein Raster-PNG-Bild, bevor sie in die Präsentation eingefügt werden.


## add_image(self, stream) {#iorawiobase}
Fügt ein Bild zu einer Präsentation aus einem Stream hinzu.

### Rückgabe

Hinzugefügtes Bild.



```python
def add_image(self, stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, aus dem das Bild hinzugefügt werden soll. |

### Hinweise

Diese Methode kann WMF/EMF-Metadateien zu einer Präsentation hinzufügen, ohne sie in ein Raster-PNG-Bild zu konvertieren.


## add_image(self, buffer) {#bytes}
Fügt ein Bild zu einer Präsentation aus einem angegebenen Puffer hinzu.

### Rückgabe

Hinzugefügtes Bild.



```python
def add_image(self, buffer):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| buffer | **bytes** | Puffer. |


## add_image(self, svg_image) {#isvgimage}
Fügt ein Bild zu einer Präsentation aus einem Svg-Objekt hinzu.

### Rückgabe

Hinzugefügtes Bild.



```python
def add_image(self, svg_image):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage) | Svg-Bildobjekt [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage) |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wenn der Parameter svgImage None ist. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Erstellt und fügt ein Bild zu einer Präsentation aus einem Stream hinzu.

### Rückgabe

Hinzugefügtes [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, aus dem die Bilddatei hinzugefügt werden soll. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/de/aspose.slides/loadingstreambehavior) | Das Verhalten, das auf den Stream angewendet wird. |



### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Klasse [`ImageCollection`](/slides/python-net/de/aspose.slides/imagecollection)
* Klasse [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage)
* Klasse [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage)
* Aufzählung [`LoadingStreamBehavior`](/slides/python-net/de/aspose.slides/loadingstreambehavior)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)