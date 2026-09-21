---
title: insert_section_zoom_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
สร้าง Section Zoom frame ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ

### ผลลัพธ์

ออบเจกต์ใหม่ที่สร้างขึ้น [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ที่ใช้ในการแทรก Section Zoom frame |
| x | **float** | พิกัด x ของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| section | [`ISection`](/slides/python-net/th/aspose.slides/isection) | [`ISection`](/slides/python-net/th/aspose.slides/isection) ที่อ้างอิงโดย Section Zoom frame;<br/><br/>ต้องเป็นของงานนำเสนอปัจจุบันและต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นหาก section ที่อ้างอิงไม่ได้เป็นของงานนำเสนอปัจจุบันหรือไม่มีสไลด์ |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
สร้าง Section Zoom frame ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ

### ผลลัพธ์

ออบเจกต์ใหม่ที่สร้างขึ้น [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีเริ่มจากศูนย์ที่ใช้ในการแทรก Section Zoom frame |
| x | **float** | พิกัด x ของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| width | **float** | ความกว้างของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| height | **float** | ความสูงของ Section Zoom frame ใหม่, หน่วยเป็นจุด |
| section | [`ISection`](/slides/python-net/th/aspose.slides/isection) | [`ISection`](/slides/python-net/th/aspose.slides/isection) ที่อ้างอิงโดย Section Zoom frame;<br/><br/>ต้องเป็นของงานนำเสนอปัจจุบันและต้องมีสไลด์อย่างน้อยหนึ่งสไลด์ |
| image | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | ภาพที่จะแสดงภายใน Section Zoom frame |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นหาก section ที่อ้างอิงไม่ได้เป็นของงานนำเสนอปัจจุบันหรือไม่มีสไลด์ |



### ดูเพิ่มเติม
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`ISection`](/slides/python-net/th/aspose.slides/isection)
* คลาส [`ISectionZoomFrame`](/slides/python-net/th/aspose.slides/isectionzoomframe)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)