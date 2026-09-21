---
title: to_tiff method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API เอกสารอ้างอิง
description: 
type: docs
url: /th/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
แปลงพรีเซนเทชันต้นทางเป็นชุดของภาพรูปแบบ TIFF.  
            หากระบุชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.tiff", ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.tiff" ซึ่ง N คือหมายเลขสไลด์.


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | พรีเซนเทชันต้นทาง |
| output_file_name | **str** | ชื่อไฟล์ผลลัพธ์ |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
แปลงพรีเซนเทชันต้นทางเป็นรูปแบบ TIFF พร้อมตัวเลือกที่กำหนดเอง.  
            หากระบุชื่อไฟล์ผลลัพธ์เป็น "myPath/myFilename.tiff" และ `multipage` มีค่าเป็น `false`, ผลลัพธ์จะถูกบันทึกเป็นชุดของไฟล์ "myPath/myFilename_N.tiff" ซึ่ง N คือหมายเลขสไลด์.  
            หาก `multipage` มีค่าเป็น `true`, ผลลัพธ์จะเป็นเอกสารหลายหน้า "myPath/myFilename.tiff".


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/th/aspose.slides/presentation) | พรีเซนเทชันต้นทาง |
| output_file_name | **str** | ชื่อไฟล์ผลลัพธ์ |
| options | [`ITiffOptions`](/slides/python-net/th/aspose.slides.export/itiffoptions) | ตัวเลือกการบันทึก TIFF |
| multipage | **bool** | ระบุว่าต้องการให้เอกสาร TIFF ที่สร้างเป็นหลายหน้าหรือไม่ |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### ดูเพิ่มเติม
* คลาส [`Convert`](/slides/python-net/th/aspose.slides.lowcode/convert)
* คลาส [`ITiffOptions`](/slides/python-net/th/aspose.slides.export/itiffoptions)
* คลาส [`Presentation`](/slides/python-net/th/aspose.slides/presentation)
* โมดูล [`aspose.slides.lowcode`](/slides/python-net/th/aspose.slides.lowcode)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)