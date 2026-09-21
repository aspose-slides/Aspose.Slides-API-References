---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/pictureframe/get_image/
weight: 50
---
## get_image(self) {#}
คืนค่า shape thumbnail.
            ประเภทของขอบเขต shape thumbnail ของ ShapeThumbnailBounds.Shape จะถูกใช้เป็นค่าเริ่มต้น.

### ผลลัพธ์

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
คืนค่า shape thumbnail.

### ผลลัพธ์

Shape thumbnail หรือ None ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และรูปไม่มีองค์ประกอบที่มองเห็นได้.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds) | ประเภทของขอบเขต shape thumbnail |
| scale_x | **float** | สเกล X |
| scale_y | **float** | สเกล Y |



### ดูเพิ่มเติม
* class [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* class [`PictureFrame`](/slides/python-net/th/aspose.slides/pictureframe)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/th/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)