---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/zoomobject/get_image/
weight: 30
---
## get_image(self) {#}
คืนค่าภาพย่อของรูปร่าง.
ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### ผลลัพธ์

ภาพย่อของรูปร่าง.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
คืนค่าภาพย่อของรูปร่าง.

### ผลลัพธ์

ภาพย่อของรูปร่าง หรือ None ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และรูปร่างไม่มีองค์ประกอบที่มองเห็นได้.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds) | ประเภทขอบเขตภาพย่อของรูปร่าง. |
| scale_x | **float** | การสเกล X |
| scale_y | **float** | สเกล Y |



### ดูเพิ่มเติม
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* enum [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* คลาส [`ZoomObject`](/slides/python-net/th/aspose.slides/zoomobject)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)