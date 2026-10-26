---
title: get_image method
second_title: Aspose.Slides for Python via .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/table/get_image/
weight: 30
---
## get_image(self) {#}
Visszaadja a Shape thumbnail-t.  
A ShapeThumbnailBounds.Shape shape thumbnail bounds típus az alapértelmezett.

### Returns

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Visszaadja a Shape thumbnail-t.

### Returns

Shape thumbnail vagy None, ha a ShapeThumbnailBounds.Appearance van használatban, és a shape nem rendelkezik látható elemekkel.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds típus. |
| scale_x | **float** | X skála |
| scale_y | **float** | Y skála |



### See Also
* class [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/hu/aspose.slides/shapethumbnailbounds)
* class [`Table`](/slides/python-net/hu/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)