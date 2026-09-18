---
title: get_images method
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API Referenciája
description: 
type: docs
url: /hu/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Visszaad egy Thumbnail Image objektumot a bemutató összes diájához.

### Returns

Bitmap objektumok.



```python
def get_images(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Visszaad egy Thumbnail Bitmap objektumot a megadott diákhoz a bemutatóban.

### Returns

Bitmap objektumok.



```python
def get_images(self, options, slides):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |
| slides | **List[int]** | Tömb a dia pozíciókkal, 1-től kezdve. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Visszaad egy Thumbnail Image objektumot a bemutató összes diájához a megadott mérettel.

### Returns

Bitmap objektumok.



```python
def get_images(self, options, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |
| image_size | **aspose.slides.Size** | A létrehozandó kép mérete. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Visszaad egy Thumbnail Image objektumot a bemutató összes diájához egyedi méretezéssel.

### Returns

Bitmap objektumok.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |
| scale_x | **float** | Az a érték, amellyel ezt a Thumbnail-et az x-tengely irányában méretezi. |
| scale_y | **float** | Az a érték, amellyel ezt a Thumbnail-et az y-tengely irányában méretezi. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Visszaad egy Thumbnail Image objektumot a megadott diákhoz a bemutatóban a megadott mérettel.

### Returns

Bitmap objektumok.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |
| slides | **List[int]** | Tömb a dia pozíciókkal, 1-től kezdve. |
| image_size | **aspose.slides.Size** | A létrehozandó kép mérete. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Visszaad egy Thumbnail Image objektumot a megadott diákhoz a bemutatóban egyedi méretezéssel.

### Returns

Bitmap objektumok.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Renderelési opciók. |
| slides | **List[int]** | Tömb a dia pozíciókkal, 1-től kezdve. |
| scale_x | **float** | Az a érték, amellyel ezt a Thumbnail-et az x-tengely irányában méretezi. |
| scale_y | **float** | Az a érték, amellyel ezt a Thumbnail-et az y-tengely irányában méretezi. |



### See Also
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* osztály [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)