---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishape/get_image/
weight: 30
---
## get_image(self) {#}
ส่งคืนภาพย่อของรูปร่าง
ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### ผลลัพธ์

ภาพย่อของรูปร่าง.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
ส่งคืนภาพย่อของรูปร่าง.

### ผลลัพธ์

ภาพย่อของรูปร่าง หรือ None ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และรูปร่างไม่มีส่วนที่มองเห็นได้.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds) | ประเภทของขอบเขตภาพย่อของรูปร่าง |
| scale_x | **float** | สเกล X |
| scale_y | **float** | สเกล Y |

### ดูเพิ่มเติม
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* คลาส [`IShape`](/slides/python-net/th/aspose.slides/ishape)
* การนับค่า [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)