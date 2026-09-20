---
title: add_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
Lägger till en kopia av en bild från en annan presentation.

### Returnerar

Tillagd bild.



```python
def add_image(self, image_source):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage) | Källbild. |


## add_image(self, image) {#iimage}
Lägger till en bild i en presentation.

### Returnerar

Tillagd bild.



```python
def add_image(self, image):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/sv/aspose.slides/iimage) | Bild att lägga till. |

### Anmärkningar

Denna metod konverterar WMF/EMF-metafiler till raster-PNG-bild innan den infogas i en presentation.


## add_image(self, stream) {#iorawiobase}
Lägger till en bild i en presentation från en ström.

### Returnerar

Tillagd bild.



```python
def add_image(self, stream):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ström att lägga till bild från. |

### Anmärkningar

Denna metod kan lägga till WMF/EMF-metafiler i en presentation utan att konvertera dem till raster-PNG-bild.


## add_image(self, buffer) {#bytes}
Lägger till en bild i en presentation från en specificerad buffer.

### Returnerar

Tillagd bild.



```python
def add_image(self, buffer):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image(self, svg_image) {#isvgimage}
Lägger till en bild i en presentation från ett Svg-objekt.

### Returnerar

Tillagd bild.



```python
def add_image(self, svg_image):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/sv/aspose.slides/isvgimage) | Svg-bildobjekt [`ISvgImage`](/slides/python-net/sv/aspose.slides/isvgimage) |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | När svgImage-parameter är None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Skapar och lägger till en bild i en presentation från en ström.

### Returnerar

Tillagd [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ström att lägga till bildfil från. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/sv/aspose.slides/loadingstreambehavior) | Det beteende som kommer att tillämpas på strömmen. |



### Se även
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* klass [`ImageCollection`](/slides/python-net/sv/aspose.slides/imagecollection)
* klass [`IPPImage`](/slides/python-net/sv/aspose.slides/ippimage)
* klass [`ISvgImage`](/slides/python-net/sv/aspose.slides/isvgimage)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/sv/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)