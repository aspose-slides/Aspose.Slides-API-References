---
title: get_image method
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
ส่งคืน shape thumbnail.
ShapeThumbnailBounds.Shape shape thumbnail bounds type ถูกใช้เป็นค่าเริ่มต้น.

### ค่าที่ส่งคืน

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
ส่งคืน shape thumbnail.

### ค่าที่ส่งคืน

Shape thumbnail หรือ None หาก ShapeThumbnailBounds.Appearance ถูกใช้และ shape ไม่มีองค์ประกอบที่มองเห็นได้.



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
* คลาส [`Ink`](/slides/python-net/th/aspose.slides.ink/ink)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* โมดูล [`aspose.slides.ink`](/slides/python-net/th/aspose.slides.ink)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)