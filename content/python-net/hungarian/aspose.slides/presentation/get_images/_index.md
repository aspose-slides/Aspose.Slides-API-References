---
title: get_images method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Visszaad Image objektumokat a prezentáció összes diájához.

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
Visszaad Thumbnail Image objektumokat a prezentáció meghatározott diáihoz.

### Visszatérési érték

Image objektumok.



```python
def get_images(self, options, slides):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Tiff beállítások. |
| slides | **List[int]** | Tömb a dia pozíciókkal, 1-től kezdődően. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Visszaad Thumbnail Image objektumokat a prezentáció összes diájához a megadott mérettel.

### Visszatérési érték

Image objektumok.



```python
def get_images(self, options, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Tiff beállítások. |
| image_size | **aspose.slides.Size** | A létrehozandó kép mérete. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Visszaad Thumbnail Image objektumokat a prezentáció összes diájához egyedi méretezéssel.

### Visszatérési érték

Image objektumok.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Tiff beállítások. |
| scale_x | **float** | Az érték, amellyel ezt a Thumbnail-t az x-tengelyen méretezni kell. |
| scale_y | **float** | Az érték, amellyel ezt a Thumbnail-t az y-tengelyen méretezni kell. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Visszaad Thumbnail Image objektumokat a prezentáció meghatározott diáihoz a megadott mérettel.

### Visszatérési érték

Image objektumok.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Tiff beállítások. |
| slides | **List[int]** | Tömb a dia pozíciókkal, 1-től kezdődően. |
| image_size | **aspose.slides.Size** | A létrehozandó kép mérete. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Visszaad Thumbnail Image objektumokat a prezentáció meghatározott diáihoz egyedi méretezéssel.

### Visszatérési érték

Image objektumok.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions) | Tiff beállítások. |
| slides | **List[int]** | Tömb a dia pozíciókkal, 1-től kezdődően. |
| scale_x | **float** | Az érték, amellyel ezt a Thumbnail-t az x-tengelyen méretezni kell. |
| scale_y | **float** | Az érték, amellyel ezt a Thumbnail-t az y-tengelyen méretezni kell. |



### Lásd még
* class [`IRenderingOptions`](/slides/python-net/hu/aspose.slides.export/irenderingoptions)
* class [`Presentation`](/slides/python-net/hu/aspose.slides/presentation)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)