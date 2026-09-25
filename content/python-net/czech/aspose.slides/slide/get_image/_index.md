---
title: get_image method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Vrací objekt Thumbnail Image (20 % skutečné velikosti).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Vrací objekt Thumbnail Image se zadanou velikostí.

### Návratová hodnota

Objekt Image.



```python
def get_image(self, image_size):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/cs/aspose.slides/size) | Velikost obrázku, který se vytvoří. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Vrací objekt Thumbnail tiff image se zadanými parametry.

### Návratová hodnota

Objekt Image.



```python
def get_image(self, options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/cs/aspose.slides.export/itiffoptions) | Možnosti Tiff. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvoláno, když options.SlideLayoutOption je NotesCommentsLayoutingOptions a jeho vlastnost NotesPosition má hodnotu NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Vrací objekt Thumbnail Image.

### Návratová hodnota

Objekt Image.



```python
def get_image(self, options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti vykreslování. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvoláno, když notesCommentsLayouting.NotesPosition má hodnotu NotesPositions.BottomFull. |


## get_image(self, scale_x, scale_y) {#float-float}
Vrací objekt Thumbnail Image s vlastním škálováním.

### Návratová hodnota

Objekt IImage.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| scale_x | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy x. |
| scale_y | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Vrací objekt Thumbnail Image se zadanou velikostí.

### Návratová hodnota

Objekt Image.



```python
def get_image(self, options, image_size):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti vykreslování. |
| image_size | [`Size`](/slides/python-net/cs/aspose.slides/size) | Velikost obrázku, který se vytvoří. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvoláno, když options.SlideLayoutOption je NotesCommentsLayoutingOptions a jeho vlastnost NotesPosition má hodnotu NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Vrací objekt Thumbnail Image s vlastním škálováním.

### Návratová hodnota

Objekty Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti vykreslování. |
| scale_x | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy x. |
| scale_y | **float** | Hodnota, o kterou se má tento Thumbnail škálovat ve směru osy y. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvoláno, když notesCommentsLayouting.NotesPosition má hodnotu NotesPositions.BottomFull. |



### Viz také
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* třída [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions)
* třída [`ITiffOptions`](/slides/python-net/cs/aspose.slides.export/itiffoptions)
* třída [`Slide`](/slides/python-net/cs/aspose.slides/slide)
* třída [`Size`](/slides/python-net/cs/aspose.slides/size)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)