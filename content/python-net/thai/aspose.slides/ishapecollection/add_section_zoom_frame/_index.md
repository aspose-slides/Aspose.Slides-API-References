---
title: add_section_zoom_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
สร้าง Section Zoom frame ใหม่และเพิ่มลงท้ายของคอลเลกชัน shape.

### คืนค่า

อ็อบเจ็กต์ที่สร้างใหม่ [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x | **float** | ค่าพิกัด x ของ Section Zoom frame ใหม่, หน่วยเป็น points. |
| y | **float** | ค่าพิกัด y ของ Section Zoom frame ใหม่, หน่วยเป็น points. |
| width | **float** | ความกว้างของ Section Zoom frame ใหม่, หน่วยเป็น points. |
| height | **float** | ความสูงของ Section Zoom frame ใหม่, หน่วยเป็น points. |
| section | [`ISection`](/slides/python-net/th/aspose.slides/isection) | [`ISection`](/slides/python-net/th/aspose.slides/isection) ที่อ้างอิงโดย Section Zoom frame; <br/><br/>            จำเป็นต้องเป็นของการนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดข้อผิดพลาดหากส่วนที่อ้างอิงไม่เป็นของการนำเสนอปัจจุบันหรือไม่มีสไลด์. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
สร้าง Section Zoom frame ใหม่พร้อมภาพที่กำหนดล่วงหน้าและเพิ่มลงท้ายของคอลเลกชัน shape.

### คืนค่า

อ็อบเจ็กต์ที่สร้างใหม่ [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x | **float** | ค่าพิกัด x ของ Section Zoom frame ใหม่, หน่วยเป็น points. |
| y | **float** | ค่าพิกัด y ของ Section Zoom frame ใหม่, หน่วยเป็น points. |
| width | **float** | ความกว้างของ Section Zoom frame ใหม่, หน่วยเป็น points. |
| height | **float** | ความสูงของ Section Zoom frame ใหม่, หน่วยเป็น points. |
| section | [`ISection`](/slides/python-net/th/aspose.slides/isection) | [`ISection`](/slides/python-net/th/aspose.slides/isection) ที่อ้างอิงโดย Section Zoom frame; <br/><br/>            จำเป็นต้องเป็นของการนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์. |
| image | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) ที่จะแสดงภายใน Section Zoom frame. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดข้อผิดพลาดหากส่วนที่อ้างอิงไม่เป็นของการนำเสนอปัจจุบันหรือไม่มีสไลด์. |



### ดูเพิ่มเติม
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`ISection`](/slides/python-net/th/aspose.slides/isection)
* คลาส [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)