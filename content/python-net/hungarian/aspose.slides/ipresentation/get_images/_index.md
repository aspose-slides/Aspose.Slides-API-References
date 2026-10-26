---
title: get_images method
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Visszaad Thumbnail Image objektumokat a bemutató összes diájához.

### Visszatérési érték

Bitmap objektumok.



```python
def get_images(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Rendering options. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Visszaad Thumbnail Bitmap objektumokat a megadott diákhoz a bemutatóban.

### Visszatérési érték

Bitmap objektumok.



```python
def get_images(self, options, slides):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array a dia pozíciókkal, az 1-től kezdve. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Visszaad Thumbnail Image objektumokat a bemutató összes diájához a megadott mérettel.

### Visszatérési érték

Bitmap objektumok.



```python
def get_images(self, options, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Rendering options. |
| image_size | [`Size`](/slides/python-net/hu/aspose.slides/size) | A létrehozandó kép mérete. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Visszaad Thumbnail Image objektumokat a bemutató összes diájához egyedi méretezéssel.

### Visszatérési érték

Bitmap objektumok.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Rendering options. |
| scale_x | **float** | Az érték, amellyel az x-tengelyen skálázzuk ezt a Thumbnail-t. |
| scale_y | **float** | Az érték, amellyel az y-tengelyen skálázzuk ezt a Thumbnail-t. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Visszaad Thumbnail Image objektumokat a megadott diákhoz a bemutatóban a megadott mérettel.

### Visszatérési érték

Bitmap objektumok.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array a dia pozíciókkal, az 1-től kezdve. |
| image_size | [`Size`](/slides/python-net/hu/aspose.slides/size) | A létrehozandó kép mérete. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Visszaad Thumbnail Image objektumokat a megadott diákhoz a bemutatóban egyedi méretezéssel.

### Visszatérési érték

Bitmap objektumok.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Rendering options. |
| slides | **List[int]** | Array a dia pozíciókkal, az 1-től kezdve. |
| scale_x | **float** | Az érték, amellyel az x-tengelyen skálázzuk ezt a Thumbnail-t. |
| scale_y | **float** | Az érték, amellyel az y-tengelyen skálázzuk ezt a Thumbnail-t. |



### Lásd még
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* osztály [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions)
* osztály [`Size`](/slides/python-net/hu/aspose.slides/size)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)