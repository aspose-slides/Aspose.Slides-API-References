---
title: insert_section_zoom_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
สร้างเฟรม Section Zoom ใหม่และแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ

### Returns
ผลลัพธ์

ออบเจ็กต์ที่สร้างใหม่ [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ที่ใช้แทรก Section Zoom frame |
| x | **float** | พิกัด x ของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| section | [`ISection`](/slides/python-net/th/aspose.slides/isection) | [`ISection`](/slides/python-net/th/aspose.slides/isection) ที่อ้างอิงโดย Section Zoom frame;<br/><br/>            ต้องเป็นของงานนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |

### Exceptions

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | จะเกิดขึ้นหากส่วนที่อ้างอิงไม่เป็นของงานนำเสนอปัจจุบันหรือไม่มีสไลด์ใดๆ |

## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
สร้าง Section Zoom frame ใหม่โดยมีภาพที่กำหนดไว้ล่วงหน้าและแทรกลงในคอลเลกชันรูปทรงที่ตำแหน่งที่ระบุ

### Returns
ผลลัพธ์

ออบเจ็กต์ที่สร้างใหม่ [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ที่ใช้แทรก Section Zoom frame |
| x | **float** | พิกัด x ของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| section | [`ISection`](/slides/python-net/th/aspose.slides/isection) | [`ISection`](/slides/python-net/th/aspose.slides/isection) ที่อ้างอิงโดย Section Zoom frame;<br/><br/>            ต้องเป็นของงานนำเสนอนี้และต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |
| image | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | ภาพที่จะแสดงภายใน Section Zoom frame |

### Exceptions

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | จะเกิดขึ้นหากส่วนที่อ้างอิงไม่เป็นของงานนำเสนอปัจจุบันหรือไม่มีสไลด์ใด ๆ |



### See Also
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`ISection`](/slides/python-net/th/aspose.slides/isection)
* คลาส [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)