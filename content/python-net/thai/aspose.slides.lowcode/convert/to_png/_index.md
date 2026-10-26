---
title: to_png method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
แปลงการนำเสนออินพุตเป็นชุดของภาพรูปแบบ PNG  
หากชื่อไฟล์ผลลัพธ์ระบุเป็น "myPath/myFilename.png", ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename_N.png" ไฟล์, โดยที่ N คือหมายเลขสไลด์


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | การนำเสนออินพุต |
| output_file_name | **str** | ชื่อไฟล์ผลลัพธ์ |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
แปลงการนำเสนออินพุตเป็นชุดของภาพรูปแบบ PNG  
หากชื่อไฟล์ผลลัพธ์ระบุเป็น "myPath/myFilename.png", ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename_N.png" ไฟล์, โดยที่ N คือหมายเลขสไลด์


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | การนำเสนออินพุต |
| output_file_name | **str** | ชื่อไฟล์ผลลัพธ์ |
| image_size | [`Size`](/slides/python-net/th/aspose.slides/size) | ขนาดของแต่ละภาพที่สร้างขึ้น |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
แปลงการนำเสนออินพุตเป็นชุดของภาพรูปแบบ PNG  
หากชื่อไฟล์ผลลัพธ์ระบุเป็น "myPath/myFilename.png", ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename_N.png" ไฟล์, โดยที่ N คือหมายเลขสไลด์


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | การนำเสนออินพุต |
| output_file_name | **str** | ชื่อไฟล์ผลลัพธ์ |
| scale | **float** | ปัจจัยการปรับสเกลที่ใช้กับภาพผลลัพธ์เทียบกับขนาดสไลด์ต้นฉบับ |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการแเรนเดอร์ |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### ดูเพิ่มเติม
* คลาส [`Convert`](/slides/python-net/th/aspose.slides.lowcode/convert)
* คลาส [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions)
* คลาส [`Presentation`](/slides/python-net/th/aspose.slides/presentation)
* คลาส [`Size`](/slides/python-net/th/aspose.slides/size)
* โมดูล [`aspose.slides.lowcode`](/slides/python-net/th/aspose.slides.lowcode)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)