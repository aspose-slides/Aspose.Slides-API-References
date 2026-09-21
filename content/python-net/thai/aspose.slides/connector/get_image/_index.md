---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
คืนค่าภาพย่อของรูปร่าง
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### คืนค่า

ภาพย่อของรูปร่าง.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
คืนค่าภาพย่อของรูปร่าง

### คืนค่า

ภาพย่อของรูปร่างหรือ None ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และรูปร่างไม่มีส่วนที่มองเห็นได้.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds) | ประเภทขอบเขตของรูปย่อของรูปร่าง |
| scale_x | **float** | สเกล X |
| scale_y | **float** | สเกล Y |



### ดูเพิ่มเติม
* คลาส [`Connector`](/slides/python-net/th/aspose.slides/connector)
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)