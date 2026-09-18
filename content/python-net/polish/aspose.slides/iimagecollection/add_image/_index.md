---
title: add_image method
second_title: Aspose.Slides dla Pythona via .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Dodaj obraz do prezentacji.

### Zwraca

Dodany obraz.



```python
def add_image(self, image):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/pl/aspose.slides/iimage) | Obraz do dodania. |

### Uwagi

Ta metoda konwertuje pliki metafile WMF/EMF na rastrowy obraz PNG przed wstawieniem do prezentacji.


## add_image(self, stream) {#iorawiobase}
Dodaj obraz do prezentacji ze strumienia.

### Zwraca

Dodany obraz.



```python
def add_image(self, stream):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień, z którego dodać obraz. |

### Uwagi

Ta metoda może dodać pliki metafile WMF/EMF do prezentacji bez konwertowania ich na rastrowy obraz PNG.


## add_image(self, buffer) {#bytes}
Dodaje obraz do prezentacji z określonego bufora.

### Zwraca

Dodany obraz.



```python
def add_image(self, buffer):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| buffer | **bytes** | Bufor. |


## add_image(self, image_source) {#ippimage}
Dodaje kopię obrazu z innej prezentacji.

### Zwraca

Dodany obraz.



```python
def add_image(self, image_source):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage) | Obraz źródłowy. |


## add_image(self, svg_image) {#isvgimage}
Dodaj obraz do prezentacji z obiektu SVG.

### Zwraca

Dodany obraz.



```python
def add_image(self, svg_image):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/pl/aspose.slides/isvgimage) | Obiekt obrazu SVG [`ISvgImage`](/slides/python-net/pl/aspose.slides/isvgimage) |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Rzucany, gdy parametr svgImage jest None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Tworzy i dodaje obraz do prezentacji ze strumienia.

### Zwraca

Dodano [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień, z którego dodać plik obrazu. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/pl/aspose.slides/loadingstreambehavior) | Zachowanie, które zostanie zastosowane do strumienia. |



### Zobacz także
* klasa [`IImage`](/slides/python-net/pl/aspose.slides/iimage)
* klasa [`IImageCollection`](/slides/python-net/pl/aspose.slides/iimagecollection)
* klasa [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage)
* klasa [`ISvgImage`](/slides/python-net/pl/aspose.slides/isvgimage)
* enumeracja [`LoadingStreamBehavior`](/slides/python-net/pl/aspose.slides/loadingstreambehavior)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)