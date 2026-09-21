---
title: get_image method
second_title: การอ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides.smartart/smartartshape/get_image/
weight: 50
---
## get_image(self) {#}
คืนค่า Shape thumbnail.
ShapeThumbnailBounds.Shape shape thumbnail bounds type ถูกใช้เป็นค่าเริ่มต้น.

### คืนค่า

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
คืนค่า Shape thumbnail.

### คืนค่า

Shape thumbnail หรือ None ในกรณีที่ ShapeThumbnailBounds.Appearance ถูกใช้และ shape ไม่มีองค์ประกอบที่มองเห็นได้.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | สเกล X |
| scale_y | **float** | สเกล Y |



### ดูเพิ่มเติม
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* การนับ [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* คลาส [`SmartArtShape`](/slides/python-net/th/aspose.slides.smartart/smartartshape)
* โมดูล [`aspose.slides.smartart`](/slides/python-net/th/aspose.slides.smartart)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)