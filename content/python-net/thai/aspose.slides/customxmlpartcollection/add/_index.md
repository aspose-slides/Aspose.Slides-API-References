---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
เพิ่มส่วน xml แบบกำหนดเองใหม่.

### คืนค่า

สร้างส่วน xml แบบกำหนดเองแล้ว.



```python
def add(self, xml_string):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| xml_string | **str** | สตริง xml ของส่วนใหม่ที่ต้องการเพิ่ม. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString เป็น `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString ว่างเปล่าหรือข้อมูล xml ไม่ถูกต้อง. |


## add(self, xml_data) {#bytes}
เพิ่มส่วน xml แบบกำหนดเองใหม่.

### คืนค่า

สร้างส่วน xml แบบกำหนดเองแล้ว.



```python
def add(self, xml_data):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| xml_data | **bytes** | ข้อมูล xml ของส่วนใหม่ที่ต้องการเพิ่ม. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData เป็น `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData ว่างเปล่าหรือไม่ถูกต้อง. |


## add(self, input_stream) {#iorawiobase}
เพิ่มส่วน xml แบบกำหนดเองใหม่.

### คืนค่า

สร้างส่วน xml แบบกำหนดเองแล้ว.



```python
def add(self, input_stream):
    ...
```


| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | inputStream ที่มีข้อมูล xml ของส่วนใหม่ที่ต้องการเพิ่ม. |

### ข้อยกเว้น

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream เป็น `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Data ใน inputStream ว่างเปล่าหรือไม่ถูกต้อง. |



### ดูเพิ่มเติม
* คลาส [`CustomXmlPartCollection`](/slides/python-net/th/aspose.slides/customxmlpartcollection)
* คลาส [`ICustomXmlPart`](/slides/python-net/th/aspose.slides/icustomxmlpart)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)