---
title: to_jpeg method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
แปลงงานนำเสนออินพุตเป็นชุดของภาพรูปแบบ JPEG.  
            หากกำหนดชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.jpeg", 
            ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename_N.jpeg" ไฟล์, โดยที่ N คือหมายเลขสไลด์.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | งานนำเสนออินพุต. |
| output_file_name | **str** | ชื่อไฟล์ผลลัพธ์. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
แปลงงานนำเสนออินพุตเป็นชุดของภาพรูปแบบ JPEG.  
            หากกำหนดชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.jpeg", 
            ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename_N.jpeg" ไฟล์, โดยที่ N คือหมายเลขสไลด์.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | งานนำเสนออินพุต |
| output_file_name | **str** | ชื่อไฟล์ผลลัพธ์. |
| image_size | **aspose.slides.Size** | ขนาดของแต่ละภาพที่สร้างขึ้น. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
แปลงงานนำเสนออินพุตเป็นชุดของภาพรูปแบบ JPEG.  
            หากกำหนดชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.jpeg", 
            ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename_N.jpeg" ไฟล์, โดยที่ N คือหมายเลขสไลด์.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | งานนำเสนออินพุต. |
| output_file_name | **str** | ชื่อไฟล์ผลลัพธ์. |
| scale | **float** | ปัจจัยสเกลที่ใช้กับภาพผลลัพธ์เทียบกับขนาดสไลด์ต้นฉบับ. |
| options | [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions) | ตัวเลือกการเรนเดอร์. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### ดูเพิ่มเติม
* คลาส [`Convert`](/slides/python-net/th/aspose.slides.lowcode/convert)
* คลาส [`IRenderingOptions`](/slides/python-net/th/aspose.slides.export/irenderingoptions)
* คลาส [`Presentation`](/slides/python-net/th/aspose.slides/presentation)
* โมดูล [`aspose.slides.lowcode`](/slides/python-net/th/aspose.slides.lowcode)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)