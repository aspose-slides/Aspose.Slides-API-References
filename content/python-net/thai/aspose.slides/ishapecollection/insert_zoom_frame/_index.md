---
title: insert_zoom_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
สร้าง Zoom frame ใหม่และแทรกลงในคอลเลกชันของ shape ที่ตำแหน่งที่ระบุ

### ผลลัพธ์

[`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe) ที่สร้างใหม่

```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใช้เพื่อแทรก Zoom frame |
| x | **float** | พิกัด x ของ Zoom frame ใหม่, หน่วยเป็น point |
| y | **float** | พิกัด y ของ Zoom frame ใหม่, หน่วยเป็น point |
| width | **float** | ความกว้างของ Zoom frame ใหม่, หน่วยเป็น point |
| height | **float** | ความสูงของ Zoom frame ใหม่, หน่วยเป็น point |
| slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | [`ISlide`](/slides/python-net/th/aspose.slides/islide) ที่อ้างอิงโดย Zoom frame |

### ข้อยกเว้น

| ข้อยกเว่น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | จะเกิดข้อผิดพลาดหาก slide ที่อ้างอิงไม่เป็นส่วนของการนำเสนอปัจจุบัน |

## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
สร้าง Zoom frame ใหม่พร้อมภาพที่กำหนดไว้ล่วงหน้าและแทรกลงในคอลเลกชันของ shape ที่ตำแหน่งที่ระบุ

### ผลลัพธ์

[`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe) ที่สร้างใหม่

```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ซึ่งจะใช้เพื่อแทรก Zoom frame |
| x | **float** | พิกัด x ของ Zoom frame ใหม่, หน่วยเป็น point |
| y | **float** | พิกัด y ของ Zoom frame ใหม่, หน่วยเป็น point |
| width | **float** | ความกว้างของ Zoom frame ใหม่, หน่วยเป็น point |
| height | **float** | ความสูงของ Zoom frame ใหม่, หน่วยเป็น point |
| slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | [`ISlide`](/slides/python-net/th/aspose.slides/islide) ที่อ้างอิงโดย Zoom frame |
| image | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | ภาพสำหรับ slide ที่อ้างอิง [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) |

### ข้อยกเว้น

| ข้อยกเว่น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | จะเกิดข้อผิดพลาดหาก slide ที่อ้างอิงไม่เป็นส่วนของการนำเสนอปัจจุบัน |

### ดูเพิ่มเติม
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* คลาส [`ISlide`](/slides/python-net/th/aspose.slides/islide)
* คลาส [`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)