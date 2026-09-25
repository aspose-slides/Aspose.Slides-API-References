---
title: get_image method
second_title: Aspose.Slides dla Pythona poprzez .NET - Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Zwraca obiekt Thumbnail Image (20% rzeczywistego rozmiaru).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Zwraca obiekt Thumbnail Image o określonym rozmiarze.

### Zwraca

Obiekt Image.



```python
def get_image(self, image_size):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/pl/aspose.slides/size) | Rozmiar obrazu do utworzenia. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Zwraca obiekt miniatury obrazu tiff z określonymi parametrami.

### Zwraca

Obiekt Image.



```python
def get_image(self, options):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/pl/aspose.slides.export/itiffoptions) | Opcje tiff. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzucany, gdy options.SlideLayoutOption jest NotesCommentsLayoutingOptions, a jego właściwość NotesPosition przyjmuje wartość NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Zwraca obiekt Thumbnail Image.

### Zwraca

Obiekt Image.



```python
def get_image(self, options):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pl/aspose.slides.export/irenderingoptions) | Opcje renderowania. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzucany, gdy notesCommentsLayouting.NotesPosition przyjmuje wartość NotesPositions.BottomFull |


## get_image(self, scale_x, scale_y) {#float-float}
Zwraca obiekt Thumbnail Image ze skalowaniem niestandardowym.

### Zwraca

Obiekt IImage.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| scale_x | **float** | Wartość, o którą skalować tę miniaturę w kierunku osi x. |
| scale_y | **float** | Wartość, o którą skalować tę miniaturę w kierunku osi y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Zwraca obiekt Thumbnail Image o określonym rozmiarze.

### Zwraca

Obiekt Image.



```python
def get_image(self, options, image_size):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pl/aspose.slides.export/irenderingoptions) | Opcje renderowania. |
| image_size | [`Size`](/slides/python-net/pl/aspose.slides/size) | Rozmiar obrazu do utworzenia. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzucany, gdy options.SlideLayoutOption jest NotesCommentsLayoutingOptions, a jego właściwość NotesPosition przyjmuje wartość NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Zwraca obiekt Thumbnail Image ze skalowaniem niestandardowym.

### Zwraca

Obiekty Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/pl/aspose.slides.export/irenderingoptions) | Opcje renderowania. |
| scale_x | **float** | Wartość, o którą skalować tę miniaturę w kierunku osi x. |
| scale_y | **float** | Wartość, o którą skalować tę miniaturę w kierunku osi y. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzucany, gdy notesCommentsLayouting.NotesPosition przyjmuje wartość NotesPositions.BottomFull |



### Zobacz także
* klasa [`IImage`](/slides/python-net/pl/aspose.slides/iimage)
* klasa [`IRenderingOptions`](/slides/python-net/pl/aspose.slides.export/irenderingoptions)
* klasa [`ITiffOptions`](/slides/python-net/pl/aspose.slides.export/itiffoptions)
* klasa [`Slide`](/slides/python-net/pl/aspose.slides/slide)
* klasa [`Size`](/slides/python-net/pl/aspose.slides/size)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)