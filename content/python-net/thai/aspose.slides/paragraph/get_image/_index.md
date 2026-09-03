---
title: get_image method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
คืนภาพของย่อหน้า

### คืนค่า
An image containing the rendered paragraph, or **None**
             หากไม่พบย่อหน้าในคอลเลกชันของพาเรนต์, ไม่มีขอบเขตการเรนเดอร์ที่ถูกต้อง, หรือเกิดข้อผิดพลาดขณะเรนเดอร์ภาพ.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
คืนภาพของย่อหน้าด้วยสเกลที่ระบุ

### คืนค่า
An image containing the rendered paragraph, or **None**
             หากไม่พบย่อหน้าในคอลเลกชันของพาเรนต์, ไม่มีขอบเขตการเรนเดอร์ที่ถูกต้อง, หรือเกิดข้อผิดพลาดขณะเรนเดอร์ภาพ.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| scale_x | **float** | ตัวคูณสเกลแนวนอนที่ใช้กับภาพย่อหน้า |
| scale_y | **float** | ตัวคูณสเกลแนวตั้งที่ใช้กับภาพย่อหน้า |



### ดูเพิ่มเติม
* คลาส [`IImage`](/slides/python-net/th/aspose.slides/iimage)
* คลาส [`Paragraph`](/slides/python-net/th/aspose.slides/paragraph)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)