---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/table/get_image/
weight: 30
---
## get_image(self) {#}
คืนค่า shape ภาพย่อ.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type ถูกใช้เป็นค่าเริ่มต้น.

### คืนค่า

Shape thumbnail.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
คืนค่า shape ภาพย่อ.

### คืนค่า

Shape thumbnail หรือ None ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และ shape ไม่มีองค์ประกอบที่มองเห็นได้.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | สเกล X |
| scale_y | **float** | สเกล Y |

### ดูเพิ่มเติม
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* คลาส [`Table`](/slides/python-net/th/aspose.slides/table)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)