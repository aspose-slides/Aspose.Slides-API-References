---
title: add_image method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
Přidá kopii obrázku z jiné prezentace.

### Návrat

Přidaný obrázek.



```python
def add_image(self, image_source):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | Source image. |


## add_image(self, image) {#iimage}
Přidá obrázek do prezentace.

### Návrat

Přidaný obrázek.



```python
def add_image(self, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/cs/aspose.slides/iimage) | Image to add. |

### Poznámky

Tato metoda převádí WMF/EMF metafily na rastrový PNG obrázek před vložením do prezentace.


## add_image(self, stream) {#iorawiobase}
Přidá obrázek do prezentace ze streamu.

### Návrat

Přidaný obrázek.



```python
def add_image(self, stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add image from. |

### Poznámky

Tato metoda může přidat WMF/EMF metafily do prezentace bez převodu na rastrový PNG obrázek.


## add_image(self, buffer) {#bytes}
Přidá obrázek do prezentace ze zadaného bufferu.

### Návrat

Přidaný obrázek.



```python
def add_image(self, buffer):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image(self, svg_image) {#isvgimage}
Přidá obrázek do prezentace z objektu Svg.

### Návrat

Přidaný obrázek.



```python
def add_image(self, svg_image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/cs/aspose.slides/isvgimage) | Objekt obrázku Svg [`ISvgImage`](/slides/python-net/cs/aspose.slides/isvgimage) |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Když je parametr svgImage nastaven na None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Vytvoří a přidá obrázek do prezentace ze streamu.

### Návrat

Přidáno [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add image file from. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/cs/aspose.slides/loadingstreambehavior) | The behavior which will be applied to the stream. |



### Viz také
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* třída [`ImageCollection`](/slides/python-net/cs/aspose.slides/imagecollection)
* třída [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* třída [`ISvgImage`](/slides/python-net/cs/aspose.slides/isvgimage)
* výčet [`LoadingStreamBehavior`](/slides/python-net/cs/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)