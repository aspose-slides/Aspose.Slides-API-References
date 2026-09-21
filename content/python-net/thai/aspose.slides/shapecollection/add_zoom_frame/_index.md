---
title: add_zoom_frame method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
สร้าง Zoom frame ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน shape

### คืนค่า

[`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe) ที่สร้างใหม่.

```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของ Zoom frame ใหม่ หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ Zoom frame ใหม่ หน่วยเป็นจุด |
| width | **float** | ความกว้างของ Zoom frame ใหม่ หน่วยเป็นจุด |
| height | **float** | ความสูงของ Zoom frame ใหม่ หน่วยเป็นจุด |
| slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | [`ISlide`](/slides/python-net/th/aspose.slides/islide) ที่อ้างอิงโดย Zoom frame;<br/><br/>ต้องเป็นของงานนำเสนอนี้ |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | ถูกโยนเมื่อสไลด์ที่อ้างอิงไม่เป็นของงานนำเสนอปัจจุบัน |

## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
สร้าง Zoom frame ใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน shape

### คืนค่า

[`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe) ที่สร้างใหม่.

```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| x | **float** | พิกัด x ของ Zoom frame ใหม่ หน่วยเป็นจุด |
| y | **float** | พิกัด y ของ Zoom frame ใหม่ หน่วยเป็นจุด |
| width | **float** | ความกว้างของ Zoom frame ใหม่ หน่วยเป็นจุด |
| height | **float** | ความสูงของ Zoom frame ใหม่ หน่วยเป็นจุด |
| slide | [`ISlide`](/slides/python-net/th/aspose.slides/islide) | [`ISlide`](/slides/python-net/th/aspose.slides/islide) ที่อ้างอิงโดย Zoom frame;<br/><br/>ต้องเป็นของงานนำเสนอนี้ |
| image | [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage) | รูปภาพสำหรับสไลด์ที่อ้างอิง [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage). |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | ถูกโยนเมื่อสไลด์ที่อ้างอิงไม่เป็นของงานนำเสนอปัจจุบัน |

### ดูเพิ่มเติม
* คลาส [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage)
* คลาส [`ISlide`](/slides/python-net/th/aspose.slides/islide)
* คลาส [`IZoomFrame`](/slides/python-net/th/aspose.slides/izoomframe)
* คลาส [`ShapeCollection`](/slides/python-net/th/aspose.slides/shapecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)