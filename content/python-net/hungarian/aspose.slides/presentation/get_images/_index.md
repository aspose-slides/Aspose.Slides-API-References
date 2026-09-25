---
title: get_images method
second_title: Aspose.Slides Python-hoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Visszaad egy Image objektumot a prezentáció összes diájához.

### Visszatérési érték

Image objektumok.



```python
def get_images(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Tiff beállítások. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban.

### Visszatérési érték

Image objektumok.



```python
def get_images(self, options, slides):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Tiff beállítások. |
| slides | **List[int]** | Tömb a diák pozícióival, kezdve 1-től. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Visszaad egy Thumbnail Image objektumot a prezentáció összes diájához a megadott mérettel.

### Visszatérési érték

Image objektumok.



```python
def get_images(self, options, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Tiff beállítások. |
| image_size | [`Size`](/slides/python-net/hu/aspose.slides/size) | A létrehozni kívánt kép mérete. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Visszaad egy Thumbnail Image objektumot a prezentáció összes diájához egyéni méretezéssel.

### Visszatérési érték

Image objektumok.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Tiff beállítások. |
| scale_x | **float** | Az az érték, amellyel ezt a bélyegképet az x tengely irányában méretezi. |
| scale_y | **float** | Az az érték, amellyel ezt a bélyegképet az y tengely irányában méretezi. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban a megadott mérettel.

### Visszatérési érték

Image objektumok.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Tiff beállítások. |
| slides | **List[int]** | Tömb a diák pozícióival, kezdve 1-től. |
| image_size | [`Size`](/slides/python-net/hu/aspose.slides/size) | A létrehozni kívánt kép mérete. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban egyéni méretezéssel.

### Visszatérési érték

Image objektumok.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Tiff beállítások. |
| slides | **List[int]** | Tömb a diák pozícióival, kezdve 1-től. |
| scale_x | **float** | Az az érték, amellyel ezt a bélyegképet az x tengely irányában méretezi. |
| scale_y | **float** | Az az érték, amellyel ezt a bélyegképet az y tengely irányában méretezi. |



### Lásd még
* osztály [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions)
* osztály [`Presentation`](/slides/python-net/hu/aspose.slides/presentation)
* osztály [`Size`](/slides/python-net/hu/aspose.slides/size)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)