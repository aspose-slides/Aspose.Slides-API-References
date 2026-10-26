---
title: add_image method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Přidá obrázek do prezentace.

### Návratová hodnota

Přidaný obrázek.



```python
def add_image(self, image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/cs/aspose.slides/iimage) | Obrázek k přidání. |

### Poznámky

Tato metoda převádí metafily WMF/EMF na rastrový PNG obrázek před vložením do prezentace.


## add_image(self, stream) {#iorawiobase}
Přidá obrázek do prezentace ze streamu.

### Návratová hodnota

Přidaný obrázek.



```python
def add_image(self, stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, ze kterého se má obrázek přidat. |

### Poznámky

Tato metoda může přidat metafily WMF/EMF do prezentace bez převodu na rastrový PNG obrázek.


## add_image(self, buffer) {#bytes}
Přidá obrázek do prezentace ze zadané vyrovnávací paměti.

### Návratová hodnota

Přidaný obrázek.



```python
def add_image(self, buffer):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| buffer | **bytes** | Vyrovnávací paměť. |


## add_image(self, image_source) {#ippimage}
Přidá kopii obrázku z jiné prezentace.

### Návratová hodnota

Přidaný obrázek.



```python
def add_image(self, image_source):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage) | Zdrojový obrázek. |


## add_image(self, svg_image) {#isvgimage}
Přidá obrázek do prezentace z objektu SVG.

### Návratová hodnota

Přidaný obrázek.



```python
def add_image(self, svg_image):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/cs/aspose.slides/isvgimage) | Objekt SVG obrázku [`ISvgImage`](/slides/python-net/cs/aspose.slides/isvgimage) |


### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Vyvoláno, když parametr svgImage je None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Vytvoří a přidá obrázek do prezentace ze streamu.

### Návratová hodnota

Přidaný [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, ze kterého se má soubor obrázku přidat. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/cs/aspose.slides/loadingstreambehavior) | Chování, které bude na stream aplikováno. |



### Viz také
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* třída [`IImageCollection`](/slides/python-net/cs/aspose.slides/iimagecollection)
* třída [`IPPImage`](/slides/python-net/cs/aspose.slides/ippimage)
* třída [`ISvgImage`](/slides/python-net/cs/aspose.slides/isvgimage)
* enumerace [`LoadingStreamBehavior`](/slides/python-net/cs/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)