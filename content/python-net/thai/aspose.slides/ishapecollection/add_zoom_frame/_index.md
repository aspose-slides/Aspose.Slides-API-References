---
title: add_zoom_frame method
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
สร้าง Zoom frame ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปทรง

### คืนค่า

อ็อบเจ็กต์ที่สร้างขึ้นใหม่ [`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของ Zoom frame ใหม่, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของ Zoom frame ใหม่, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของ Zoom frame ใหม่, หน่วยเป็นจุด. |
| height | **float** | ความสูงของ Zoom frame ใหม่, หน่วยเป็นจุด. |
| slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | [`ISlide`](/slides/python-net/th/aspose.slides/islide) ที่อ้างอิงโดย Zoom frame;<br/><br/>            ต้องเป็นของงานนำเสนอปัจจุบันนี้. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | จะถูกโยนข้อผิดพลาดหากสไลด์ที่อ้างอิงไม่ได้เป็นของงานนำเสนอปัจจุบัน. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
สร้าง Zoom frame ใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชันรูปทรง

### คืนค่า

อ็อบเจ็กต์ที่สร้างขึ้นใหม่ [`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของ Zoom frame ใหม่, หน่วยเป็นจุด. |
| y | **float** | พิกัด y ของ Zoom frame ใหม่, หน่วยเป็นจุด. |
| width | **float** | ความกว้างของ Zoom frame ใหม่, หน่วยเป็นจุด. |
| height | **float** | ความสูงของ Zoom frame ใหม่, หน่วยเป็นจุด. |
| slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | [`ISlide`](/slides/python-net/th/aspose.slides/islide) ที่อ้างอิงโดย Zoom frame;<br/><br/>            ต้องเป็นของงานนำเสนอปัจจุบันนี้. |
| image | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | ภาพสำหรับสไลด์ที่อ้างอิง [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage). |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | จะถูกโยนข้อผิดพลาดหากสไลด์ที่อ้างอิงไม่ได้เป็นของงานนำเสนอปัจจุบัน. |



### ดูเพิ่มเติม
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* คลาส [`ISlide`](/slides/python-net/th/aspose.slides/islide)
* คลาส [`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)