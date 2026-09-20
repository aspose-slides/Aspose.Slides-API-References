---
title: get_image method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
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



## get_image(self, image_size) {#asposepydrawingsize}
Vrací objekt Thumbnail Image se zadanou velikostí.

### Vrací

Objekt Image.



```python
def get_image(self, image_size):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | Velikost obrázku k vytvoření. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Vrací objekt Thumbnail tiff image se zadanými parametry.

### Vrací

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
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvolána, když options.SlideLayoutOption je NotesCommentsLayoutingOptions a její vlastnost NotesPosition má hodnotu NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Vrací objekt Thumbnail Image.

### Vrací

Objekt Image.



```python
def get_image(self, options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti renderování. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvolána, když notesCommentsLayouting.NotesPosition má hodnotu NotesPositions.BottomFull. |


## get_image(self, scale_x, scale_y) {#float-float}
Vrací objekt Thumbnail Image s vlastním měřítkem.

### Vrací

Objekt IImage.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| scale_x | **float** | Hodnota, o kterou se má tento Thumbnail měřít v ose x. |
| scale_y | **float** | Hodnota, o kterou se má tento Thumbnail měřít v ose y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Vrací objekt Thumbnail Image se zadanou velikostí.

### Vrací

Objekt Image.



```python
def get_image(self, options, image_size):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti renderování. |
| image_size | **aspose.slides.Size** | Velikost obrázku k vytvoření. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvolána, když options.SlideLayoutOption je NotesCommentsLayoutingOptions a její vlastnost NotesPosition má hodnotu NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Vrací objekt Thumbnail Image s vlastním měřítkem.

### Vrací

Objekty Bitmap.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti renderování. |
| scale_x | **float** | Hodnota, o kterou se má tento Thumbnail měřít v ose x. |
| scale_y | **float** | Hodnota, o kterou se má tento Thumbnail měřít v ose y. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvolána, když notesCommentsLayouting.NotesPosition má hodnotu NotesPositions.BottomFull. |



### Viz také
* třída [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* třída [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions)
* třída [`ITiffOptions`](/slides/python-net/cs/aspose.slides.export/itiffoptions)
* třída [`Slide`](/slides/python-net/cs/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)