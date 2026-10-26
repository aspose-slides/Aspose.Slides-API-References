---
title: insert_zoom_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
สร้างกรอบ Zoom ใหม่และแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ

### ส่งคืน

ออบเจ็กต์ที่สร้างใหม่ [`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ที่ใช้สำหรับแทรกกรอบ Zoom |
| x | **float** | พิกัด x ของกรอบ Zoom ใหม่ หน่วยเป็น point |
| y | **float** | พิกัด y ของกรอบ Zoom ใหม่ หน่วยเป็น point |
| width | **float** | ความกว้างของกรอบ Zoom ใหม่ หน่วยเป็น point |
| height | **float** | ความสูงของกรอบ Zoom ใหม่ หน่วยเป็น point |
| slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | [`ISlide`](/slides/python-net/th/aspose.slides/islide) ที่อ้างอิงโดยกรอบ Zoom |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | จะเกิดข้อยกเว้นหากสไลด์ที่อ้างอิงไม่เป็นส่วนหนึ่งของการนำเสนอปัจจุบัน |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
สร้างกรอบ Zoom ใหม่พร้อมภาพที่กำหนดล่วงหน้าและแทรกลงในคอลเลกชันรูปร่างที่ตำแหน่งที่ระบุ

### ส่งคืน

ออบเจ็กต์ที่สร้างใหม่ [`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| index | **int** | ดัชนีที่เริ่มจากศูนย์ที่ใช้สำหรับแทรกกรอบ Zoom |
| x | **float** | พิกัด x ของกรอบ Zoom ใหม่ หน่วยเป็น point |
| y | **float** | พิกัด y ของกรอบ Zoom ใหม่ หน่วยเป็น point |
| width | **float** | ความกว้างของกรอบ Zoom ใหม่ หน่วยเป็น point |
| height | **float** | ความสูงของกรอบ Zoom ใหม่ หน่วยเป็น point |
| slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | [`ISlide`](/slides/python-net/th/aspose.slides/islide) ที่อ้างอิงโดยกรอบ Zoom |
| image | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | รูปภาพสำหรับสไลด์ที่อ้างอิง [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | จะเกิดข้อยกเว้นหากสไลด์ที่อ้างอิงไม่เป็นส่วนหนึ่งของการนำเสนอปัจจุบัน |



### ดูเพิ่มเติม
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`ISlide`](/slides/python-net/th/aspose.slides/islide)
* คลาส [`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)