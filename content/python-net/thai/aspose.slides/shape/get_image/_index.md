---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/shape/get_image/
weight: 30
---
## get_image(self) {#}
ส่งคืนรูปย่อของ shape.
ใช้ประเภท ShapeThumbnailBounds.Shape shape thumbnail bounds เป็นค่าเริ่มต้น.

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
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds) | ประเภทของ shape thumbnail bounds |
| scale_x | **float** | สเกล X |
| scale_y | **float** | สเกล Y |



### ดูเพิ่มเติม
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)