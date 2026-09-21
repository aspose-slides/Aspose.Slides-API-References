---
title: add method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
เพิ่มคำบรรยายแบบปิดของ WebVTT ไปยังส่วนท้ายของคอลเลกชัน

### Returns

อินสแตนซ์ [`ICaptions`](/slides/python-net/th/aspose.slides/icaptions) ที่เพิ่มเข้ามา



```python
def add(self, label, file_path):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| label | **str** | ป้ายกำกับของคำบรรยายแบบปิด |
| file_path | **str** | พาธไปยังไฟล์ WebVTT |

### Exceptions

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เกิดขึ้นหาก `file_path` มีค่าเป็น `None` |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นหาก `file_path` ว่างเปล่า |


## add(self, label, stream) {#str-iorawiobase}
เพิ่มคำบรรยายแบบปิดของ WebVTT ไปยังส่วนท้ายของคอลเลกชันจากสตรีม

### Returns

อินสแตนซ์ [`ICaptions`](/slides/python-net/th/aspose.slides/icaptions) ที่เพิ่มเข้ามา



```python
def add(self, label, stream):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| label | **str** | ป้ายกำกับของคำบรรยายแบบปิด |
| stream | **io.RawIOBase** | สตรีมอินพุตที่มีข้อมูลในรูปแบบ WebVTT |

### Exceptions

| ข้อยกเว้น | คำอธิบาย |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | เกิดขึ้นหาก `stream` มีค่าเป็น `None` |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดขึ้นหากข้อมูลอินพุตไม่อยู่ในรูปแบบ WebVTT |



### See Also
* คลาส [`CaptionsCollection`](/slides/python-net/th/aspose.slides/captionscollection)
* คลาส [`ICaptions`](/slides/python-net/th/aspose.slides/icaptions)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)