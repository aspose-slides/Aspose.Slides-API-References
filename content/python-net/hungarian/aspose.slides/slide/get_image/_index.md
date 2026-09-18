---
title: get_image method
second_title: Aspose.Slides Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Visszaad egy Thumbnail Image objektumot (a valós méret 20%-a).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
Visszaad egy Thumbnail Image objektumot a megadott mérettel.

### Visszatérési érték

Image objektum.



```python
def get_image(self, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | A létrehozandó kép mérete. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Visszaad egy Thumbnail tiff image objektumot a megadott paraméterekkel.

### Visszatérési érték

Image objektum.



```python
def get_image(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/hu/aspose.slides.export/itiffoptions) | Tiff opciók. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel keletkezik, ha az options.SlideLayoutOption értéke NotesCommentsLayoutingOptions, és a NotesPosition tulajdonsága a NotesPositions.BottomFull értéket veszi fel. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Visszaad egy Thumbnail Image objektumot.

### Visszatérési érték

Image objektum.



```python
def get_image(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel keletkezik, ha a notesCommentsLayouting.NotesPosition a NotesPositions.BottomFull értéket veszi fel. |


## get_image(self, scale_x, scale_y) {#float-float}
Visszaad egy Thumbnail Image objektumot egyedi méretezéssel.

### Visszatérési érték

IImage objektum.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| scale_x | **float** | Az az érték, amellyel a Thumbnail-et az x-tengely irányában méretezni kell. |
| scale_y | **float** | Az az érték, amellyel a Thumbnail-et az y-tengely irányában méretezni kell. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Visszaad egy Thumbnail Image objektumot a megadott mérettel.

### Visszatérési érték

Image objektum.



```python
def get_image(self, options, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |
| image_size | **aspose.slides.Size** | A létrehozandó kép mérete. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel keletkezik, ha az options.SlideLayoutOption értéke NotesCommentsLayoutingOptions, és a NotesPosition tulajdonsága a NotesPositions.BottomFull értéket veszi fel. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Visszaad egy Thumbnail Image objektumot egyedi méretezéssel.

### Visszatérési érték

Bitmap objektumok.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |
| scale_x | **float** | Az az érték, amellyel a Thumbnail-et az x-tengely irányában méretezni kell. |
| scale_y | **float** | Az az érték, amellyel a Thumbnail-et az y-tengely irányában méretezni kell. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel keletkezik, ha a notesCommentsLayouting.NotesPosition a NotesPositions.BottomFull értéket veszi fel. |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions)
* osztály [`ITiffOptions`](/slides/python-net/hu/aspose.slides.export/itiffoptions)
* osztály [`Slide`](/slides/python-net/hu/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)