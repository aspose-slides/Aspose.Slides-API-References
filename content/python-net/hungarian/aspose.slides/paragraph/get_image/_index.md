---
title: get_image method
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
Visszaad egy képet a bekezdésről.

### Returns

An image containing the rendered paragraph, or **None**
             if the paragraph cannot be found in its parent collection, has no valid
             rendering bounds, or an error occurs while rendering the image.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Visszaad egy képet a bekezdésről a megadott skálával.

### Returns

An image containing the rendered paragraph, or **None**
             if the paragraph cannot be found in its parent collection, has no valid
             rendering bounds, or an error occurs while rendering the image.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| scale_x | **float** | A bekezdés képére alkalmazott vízszintes skálafaktor. |
| scale_y | **float** | A bekezdés képére alkalmazott függőleges skálafaktor. |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`Paragraph`](/slides/python-net/hu/aspose.slides/paragraph)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)