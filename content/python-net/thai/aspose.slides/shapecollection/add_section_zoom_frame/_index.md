---
title: add_section_zoom_frame method
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
สร้างกรอบ Section Zoom ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

### ผลลัพธ์

The newly created [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| x | **float** | พิกัด x ของกรอบ Section Zoom ใหม่, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของกรอบ Section Zoom ใหม่, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของกรอบ Section Zoom ใหม่, หน่วยเป็นจุด. |
| height | **float** | ความสูงของกรอบ Section Zoom ใหม่, หน่วยเป็นจุด. |
| section | [`ISection`](/slides/python-net/th/aspose.slides/isection) | The [`ISection`](/slides/python-net/th/aspose.slides/isection) ที่อ้างอิงโดยกรอบ Section Zoom; <br/><br/>            ต้องเป็นส่วนหนึ่งของการนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์. |

### ข้อยกเว้น

| ข้อยกเว้น | รายละเอียด |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นหากส่วนที่อ้างอิงไม่เป็นของการนำเสนอนี้หรือไม่มีสไลด์ใดๆ |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
สร้างกรอบ Section Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและเพิ่มลงในส่วนท้ายของคอลเลกชันรูปทรง

### ผลลัพธ์

The newly created [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| x | **float** | พิกัด x ของกรอบ Section Zoom ใหม่, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของกรอบ Section Zoom ใหม่, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของกรอบ Section Zoom ใหม่, หน่วยเป็นจุด. |
| height | **float** | ความสูงของกรอบ Section Zoom ใหม่, หน่วยเป็นจุด. |
| section | [`ISection`](/slides/python-net/th/aspose.slides/isection) | The [`ISection`](/slides/python-net/th/aspose.slides/isection) ที่อ้างอิงโดยกรอบ Section Zoom; <br/><br/>            ต้องเป็นส่วนหนึ่งของการนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์. |
| image | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) ที่จะแสดงภายในกรอบ Section Zoom. |

### ข้อยกเว้น

| ข้อยกเว้น | รายละเอียด |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นหากส่วนที่อ้างอิงไม่เป็นของการนำเสนอนี้หรือไม่มีสไลด์ใดๆ |



### ดูเพิ่มเติม
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`ISection`](/slides/python-net/th/aspose.slides/isection)
* คลาส [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)