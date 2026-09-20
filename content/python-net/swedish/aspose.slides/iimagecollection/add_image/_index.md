---
title: add_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Lägg till en bild i en presentation.

### Returnerar

Tillagd bild.



```python
def add_image(self, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/sv/aspose.slides/iimage) | Image to add. |

### Anmärkningar

Denna metod konverterar WMF/EMF-metafiler till raster-PNG-bild innan den infogas i en presentation.


## add_image(self, stream) {#iorawiobase}
Lägg till en bild i en presentation från en ström.

### Returnerar

Tillagd bild.



```python
def add_image(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add image from. |

### Anmärkningar

Denna metod kan lägga till WMF/EMF-metafiler i en presentation utan att konvertera dem till raster-PNG-bild.


## add_image(self, buffer) {#bytes}
Lägger till en bild i en presentation från angiven buffert.

### Returnerar

Tillagd bild.



```python
def add_image(self, buffer):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| buffer | **bytes** | Buffert. |


## add_image(self, image_source) {#ippimage}
Lägger till en kopia av en bild från en annan presentation.

### Returnerar

Tillagd bild.



```python
def add_image(self, image_source):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) | Källbild. |


## add_image(self, svg_image) {#isvgimage}
Lägg till en bild i en presentation från SVG-objekt.

### Returnerar

Tillagd bild.



```python
def add_image(self, svg_image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/sv/aspose.slides/isvgimage) | SVG-bildobjekt [`ISvgImage`](/slides/python-net/sv/aspose.slides/isvgimage) |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kastas när parametern svgImage är None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Skapar och lägger till en bild i en presentation från en ström.

### Returnerar

Tillagd [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add image file from. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/sv/aspose.slides/loadingstreambehavior) | Beteendet som kommer att tillämpas på strömmen. |



### Se även
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* klass [`IImageCollection`](/slides/python-net/sv/aspose.slides/iimagecollection)
* klass [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage)
* klass [`ISvgImage`](/slides/python-net/sv/aspose.slides/isvgimage)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/sv/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)