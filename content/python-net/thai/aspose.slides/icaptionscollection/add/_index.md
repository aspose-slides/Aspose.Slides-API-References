---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
เพิ่มคำบรรยายปิดรูปแบบ WebVTT ไปยังส่วนท้ายของคอลเลกชัน

### คืนค่า

อินสแตนซ์ [`ICaptions`](/slides/python-net/th/aspose.slides/icaptions) ที่เพิ่ม



```python
def add(self, label, file_path):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| label | **str** | ป้ายชื่อของคำบรรยายปิด |
| file_path | **str** | เส้นทางไปยังไฟล์ WebVTT |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เกิดข้อผิดพลาดหาก `file_path` เป็น `None` |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดข้อผิดพลาดหาก `file_path` ว่างเปล่า |


## add(self, label, stream) {#str-iorawiobase}
เพิ่มคำบรรยายปิดรูปแบบ WebVTT ไปยังส่วนท้ายของคอลเลกชันจากสตรีม

### คืนค่า

อินสแตนซ์ [`ICaptions`](/slides/python-net/th/aspose.slides/icaptions) ที่เพิ่ม



```python
def add(self, label, stream):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| label | **str** | ป้ายชื่อของคำบรรยายปิด |
| stream | **io.RawIOBase** | สตรีมอินพุตที่มีข้อมูลในรูปแบบ WebVTT |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เกิดข้อผิดพลาดหาก `stream` เป็น `None` |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดข้อผิดพลาดหากข้อมูลอินพุตไม่ได้อยู่ในรูปแบบ WebVTT |



### ดูเพิ่มเติม
* คลาส [`ICaptions`](/slides/python-net/th/aspose.slides/icaptions)
* คลาส [`ICaptionsCollection`](/slides/python-net/th/aspose.slides/icaptionscollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)