---
title: to_png method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
แปลงการนำเสนอที่ป้อนเข้าเป็นชุดของภาพรูปแบบ PNG.  
หากระบุชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.png" ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename_N.png" ไฟล์ โดยที่ N คือหมายเลขสไลด์.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | การนำเสนอที่ป้อนเข้า. |
| output_file_name | **str** | ชื่อไฟล์ผลลัพธ์. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
แปลงการนำเสนอที่ป้อนเข้าเป็นชุดของภาพรูปแบบ PNG.  
หากระบุชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.png" ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename_N.png" ไฟล์ โดยที่ N คือหมายเลขสไลด์.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | การนำเสนอที่ป้อนเข้า |
| output_file_name | **str** | ชื่อไฟล์ผลลัพธ์. |
| image_size | **aspose.slides.Size** | ขนาดของแต่ละภาพที่สร้างขึ้น. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
แปลงการนำเสนอที่ป้อนเข้าเป็นชุดของภาพรูปแบบ PNG.  
หากระบุชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.png" ผลลัพธ์จะถูกบันทึกเป็นชุดของ "myPath/myFilename_N.png" ไฟล์ โดยที่ N คือหมายเลขสไลด์.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | การนำเสนอที่ป้อนเข้า. |
| output_file_name | **str** | ชื่อไฟล์ผลลัพธ์. |
| scale | **float** | ปัจจัยการปรับสเกลที่ใช้กับภาพผลลัพธ์เทียบกับขนาดสไลด์ต้นฉบับ. |
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