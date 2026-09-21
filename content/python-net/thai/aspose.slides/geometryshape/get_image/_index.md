---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/geometryshape/get_image/
weight: 50
---
## get_image(self) {#}
ส่งคืนรูปย่อของ shape.
            ใช้ประเภท ShapeThumbnailBounds.Shape เป็นค่าตั้งต้น.

### คืนค่า

รูปย่อของ shape.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
ส่งคืนรูปย่อของ shape.

### คืนค่า

รูปย่อของ shape หรือ None ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และ shape ไม่มีองค์ประกอบที่มองเห็นได้.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds) | ประเภท Shape thumbnail bounds |
| scale_x | **float** | สเกล X |
| scale_y | **float** | สเกล Y |



### ดูเพิ่มเติม
* คลาส [`GeometryShape`](/slides/python-net/th/aspose.slides/geometryshape)
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)