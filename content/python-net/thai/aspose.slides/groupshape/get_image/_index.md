---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/groupshape/get_image/
weight: 30
---
## get_image(self) {#}
คืนค่า thumbnail ของ shape.  
ShapeThumbnailBounds.Shape shape thumbnail bounds type จะถูกใช้เป็นค่าเริ่มต้น.

### คืนค่า

thumbnail ของ shape.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
คืนค่า thumbnail ของ shape.

### คืนค่า

thumbnail ของ shape หรือ None ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และ shape ไม่มีองค์ประกอบที่มองเห็นได้.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds) | ประเภทของขอบเขต thumbnail ของ shape. |
| scale_x | **float** | อัตราสเกล X |
| scale_y | **float** | อัตราสเกล Y |

### ดูเพิ่มเติม
* คลาส [`GroupShape`](/slides/python-net/th/aspose.slides/groupshape)
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)