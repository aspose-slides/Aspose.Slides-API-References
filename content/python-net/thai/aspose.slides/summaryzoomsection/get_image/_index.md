---
title: get_image method
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/summaryzoomsection/get_image/
weight: 30
---
## get_image(self) {#}
ส่งคืนภาพย่อของรูปทรง.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### ส่งคืน

ภาพย่อของรูปทรง.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
ส่งคืนภาพย่อของรูปทรง.

### ส่งคืน

ภาพย่อของรูปทรง หรือ None ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และรูปทรงไม่มีองค์ประกอบที่มองเห็นได้.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds) | ประเภทขอบเขตภาพย่อของรูปทรง. |
| scale_x | **float** | สเกล X |
| scale_y | **float** | สเกล Y |

### ดูเพิ่มเติม
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* คลาส [`SummaryZoomSection`](/slides/python-net/th/aspose.slides/summaryzoomsection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)