---
title: get_image method
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
Visszaad egy miniatűr kép objektumot (20% a valós méretből).

### Visszatér

Kép objektum **aspose.slides.Bitmap**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
Visszaad egy képet a megadott mérettel.

### Visszatér

Bitmap objektum.



```python
def get_image(self, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | A létrehozandó kép mérete. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Visszaad egy miniatűr TIFF bitmap objektumot a megadott paraméterekkel.

### Visszatér

Kép objektum.



```python
def get_image(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/hu/aspose.slides.export/itiffoptions) | TIFF beállítások. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Visszaad egy miniatűr Bitmap objektumot.

### Visszatér

Bitmap objektumok.



```python
def get_image(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési beállítások. |


## get_image(self, scale_x, scale_y) {#float-float}
Visszaad egy képet egyedi méretezéssel.

### Visszatér

Kép objektum **aspose.slides.Bitmap**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| scale_x | **float** | Az az érték, amellyel a miniatűr képet az X-tengelyen skálázzuk. |
| scale_y | **float** | Az az érték, amellyel a miniatűr képet az Y-tengelyen skálázzuk. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Visszaad egy miniatűr Bitmap objektumot a megadott mérettel.

### Visszatér

Bitmap objektumok.



```python
def get_image(self, options, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési beállítások. |
| image_size | **aspose.slides.Size** | A létrehozandó kép mérete. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Visszaad egy miniatűr Bitmap objektumot egyedi méretezéssel.

### Visszatér

Bitmap objektumok.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési beállítások. |
| scale_x | **float** | Az az érték, amellyel a miniatűr képet az X-tengelyen skálázzuk. |
| scale_y | **float** | Az az érték, amellyel a miniatűr képet az Y-tengelyen skálázzuk. |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions)
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* osztály [`ITiffOptions`](/slides/python-net/hu/aspose.slides.export/itiffoptions)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)