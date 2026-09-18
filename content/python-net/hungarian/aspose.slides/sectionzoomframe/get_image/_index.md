---
title: get_image method
second_title: Aspose.Slides a Pythonhoz, .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/sectionzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Visszaadja a shape thumbnail-t.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Returns

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja a shape thumbnail-t.

### Returns

Shape thumbnail vagy None, ha a ShapeThumbnailBounds.Appearance van használatban, és a shape nem rendelkezik látható elemekkel.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds típus. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |



### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`SectionZoomFrame`](/slides/python-net/hu/aspose.slides/sectionzoomframe)
* felsorolás [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)