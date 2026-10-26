---
title: add_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Fügt ein Bild zu einer Präsentation hinzu.

### Rückgabewert
Hinzugefügtes Bild.

```python
def add_image(self, image):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/de/aspose.slides/iimage) | Hinzuzufügendes Bild. |

### Anmerkungen
Diese Methode konvertiert WMF/EMF-Metadateien in ein Raster-PNG-Bild, bevor sie in eine Präsentation eingefügt wird.

## add_image(self, stream) {#iorawiobase}
Fügt ein Bild aus einem Stream zu einer Präsentation hinzu.

### Rückgabewert
Hinzugefügtes Bild.

```python
def add_image(self, stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, aus dem das Bild hinzugefügt wird. |

### Anmerkungen
Diese Methode kann WMF/EMF-Metadateien zu einer Präsentation hinzufügen, ohne sie in ein Raster-PNG-Bild zu konvertieren.

## add_image(self, buffer) {#bytes}
Fügt ein Bild aus einem angegebenen Puffer zu einer Präsentation hinzu.

### Rückgabewert
Hinzugefügtes Bild.

```python
def add_image(self, buffer):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| buffer | **bytes** | Puffer. |

## add_image(self, image_source) {#ippimage}
Fügt eine Kopie eines Bildes aus einer anderen Präsentation hinzu.

### Rückgabewert
Hinzugefügtes Bild.

```python
def add_image(self, image_source):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) | Quellbild. |

## add_image(self, svg_image) {#isvgimage}
Fügt ein Bild aus einem SVG-Objekt zu einer Präsentation hinzu.

### Rückgabewert
Hinzugefügtes Bild.

```python
def add_image(self, svg_image):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage) | SVG-Bildobjekt [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage) |

### Ausnahmen
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wird ausgelöst, wenn der Parameter svgImage None ist. |

## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Erstellt und fügt ein Bild aus einem Stream zu einer Präsentation hinzu.

### Rückgabewert
Hinzugefügtes [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage).

```python
def add_image(self, stream, loading_stream_behavior):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, aus dem die Bilddatei hinzugefügt wird. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/de/aspose.slides/loadingstreambehavior) | Das Verhalten, das auf den Stream angewendet wird. |

### Siehe auch
* class [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* class [`IImageCollection`](/slides/python-net/de/aspose.slides/iimagecollection)
* class [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage)
* class [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/de/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)