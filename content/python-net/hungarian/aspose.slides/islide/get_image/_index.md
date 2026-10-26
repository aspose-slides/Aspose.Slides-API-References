---
title: get_image method
second_title: Aspose.Slides a .NET-en keresztül Python API referenciája
description: 
type: docs
url: /hu/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
Bélyegkép kép objektumot ad vissza (a valós méret 20 %-a).

### Visszatérési érték

Kép objektum **aspose.slides.IImage**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Megadott méretű kép objektumot ad vissza.

### Visszatérési érték

Bitmap objektum.



```python
def get_image(self, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/hu/aspose.slides/size) | A létrehozandó kép mérete. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Megadott paraméterekkel rendelkező bélyegkép-tiff bitmap objektumot ad vissza.

### Visszatérési érték

Kép objektum.



```python
def get_image(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/hu/aspose.slides.export/itiffoptions) | Tiff beállítások. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Bélyegkép Bitmap objektumot ad vissza.

### Visszatérési érték

Bitmap objektumok.



```python
def get_image(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési beállítások. |


## get_image(self, scale_x, scale_y) {#float-float}
Egyedi méretezéssel rendelkező kép objektumot ad vissza.

### Visszatérési érték

Kép objektum **aspose.slides.IImage**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| scale_x | **float** | Az érték, amely szerint a bélyegképet az x-tengely irányában méretezni kell. |
| scale_y | **float** | Az érték, amely szerint a bélyegképet az y-tengely irányában méretezni kell. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Megadott mérettel rendelkező bélyegkép Bitmap objektumot ad vissza.

### Visszatérési érték

Bitmap objektumok.



```python
def get_image(self, options, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési beállítások. |
| image_size | [`Size`](/slides/python-net/hu/aspose.slides/size) | A létrehozandó kép mérete. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Egyedi méretezéssel rendelkező bélyegkép Bitmap objektumot ad vissza.

### Visszatérési érték

Bitmap objektumok.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési beállítások. |
| scale_x | **float** | Az érték, amely szerint a bélyegképet az x-tengely irányában méretezni kell. |
| scale_y | **float** | Az érték, amely szerint a bélyegképet az y-tengely irányában méretezni kell. |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions)
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* osztály [`ITiffOptions`](/slides/python-net/hu/aspose.slides.export/itiffoptions)
* osztály [`Size`](/slides/python-net/hu/aspose.slides/size)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)