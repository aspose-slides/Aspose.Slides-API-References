---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/chart/get_image/
weight: 40
---
## get_image(self) {#}
ส่งคืนภาพย่อของรูปทรง.
ใช้ประเภทขอบเขต ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้น.

### ผลลัพธ์

ภาพย่อของรูปทรง.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
ส่งคืนภาพย่อของรูปทรง.

### ผลลัพธ์

ภาพย่อของรูปทรงหรือ None ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และรูปทรงไม่มีองค์ประกอบที่มองเห็นได้.



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
* คลาส [`Chart`](/slides/python-net/th/aspose.slides.charts/chart)
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* การระบุค่า [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)