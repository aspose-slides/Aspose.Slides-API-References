---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
ส่งคืนภาพขนาดย่อของ shape
            ShapeThumbnailBounds.Shape shape thumbnail bounds type จะถูกใช้เป็นค่าเริ่มต้น

### คืนค่า

ภาพขนาดย่อของ shape



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
ส่งคืนภาพขนาดย่อของ shape

### คืนค่า

ภาพขนาดย่อของ shape หรือ None ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และ shape ไม่มีองค์ประกอบที่มองเห็นได้



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
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* คลาส [`InkActions`](/slides/python-net/th/aspose.slides.ink/inkactions)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* โมดูล [`aspose.slides.ink`](/slides/python-net/th/aspose.slides.ink)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)