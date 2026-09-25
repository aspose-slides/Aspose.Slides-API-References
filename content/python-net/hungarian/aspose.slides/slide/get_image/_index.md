---
title: get_image method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API Referencia
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



## get_image(self, image_size) {#asposeslidessize}
Visszaad egy Thumbnail Image objektumot a megadott mérettel.

### Visszatér

Image objektum.



```python
def get_image(self, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/hu/aspose.slides/size) | A létrehozandó image mérete. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Visszaad egy Thumbnail tiff image objektumot a megadott paraméterekkel.

### Visszatér

Image objektum.



```python
def get_image(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/hu/aspose.slides.export/itiffoptions) | Tiff opciók. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel, ha az options.SlideLayoutOption a NotesCommentsLayoutingOptions, és a NotesPosition tulajdonsága a NotesPositions.BottomFull értéket veszi fel. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Visszaad egy Thumbnail Image objektumot.

### Visszatér

Image objektum.



```python
def get_image(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel, ha a notesCommentsLayouting.NotesPosition a NotesPositions.BottomFull értéket veszi fel. |


## get_image(self, scale_x, scale_y) {#float-float}
Visszaad egy Thumbnail Image objektumot egyéni méretezéssel.

### Visszatér

IImage objektum.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| scale_x | **float** | Az az érték, amellyel ezt a Thumbnail-et az x tengely irányában kell méretezni. |
| scale_y | **float** | Az az érték, amellyel ezt a Thumbnail-et az y tengely irányában kell méretezni. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Visszaad egy Thumbnail Image objektumot a megadott mérettel.

### Visszatér

Image objektum.



```python
def get_image(self, options, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |
| image_size | [`Size`](/slides/python-net/hu/aspose.slides/size) | A létrehozandó image mérete. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel, ha az options.SlideLayoutOption a NotesCommentsLayoutingOptions, és a NotesPosition tulajdonsága a NotesPositions.BottomFull értéket veszi fel. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Visszaad egy Thumbnail Image objektumot egyéni méretezéssel.

### Visszatér

Bitmap objektumok.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |
| scale_x | **float** | Az az érték, amellyel ezt a Thumbnail-et az x tengely irányában kell méretezni. |
| scale_y | **float** | Az az érték, amellyel ezt a Thumbnail-et az y tengely irányában kell méretezni. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kivétel, ha a notesCommentsLayouting.NotesPosition a NotesPositions.BottomFull értéket veszi fel. |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions)
* osztály [`ITiffOptions`](/slides/python-net/hu/aspose.slides.export/itiffoptions)
* osztály [`Slide`](/slides/python-net/hu/aspose.slides/slide)
* osztály [`Size`](/slides/python-net/hu/aspose.slides/size)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)