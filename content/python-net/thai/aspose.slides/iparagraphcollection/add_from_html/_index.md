---
title: add_from_html method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
เพิ่มข้อความจากสตริง HTML ที่ระบุไปยังคอลเลกชัน.

```python
def add_from_html(self, text):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| text | **str** | ข้อความ HTML. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
เพิ่มข้อความจากสตริง HTML ที่ระบุไปยังคอลเลกชัน.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| :- | :- | :- |
| text | **str** | ข้อความ HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver) | อ็อบเจ็กต์ callback ตัวแก้ไขที่แก้ไข URI และดึงอ็อบเจ็กต์ที่อ้างอิง. |
| uri | **str** | URI สำหรับเพิ่มเอกสาร HTML ใช้สำหรับแก้ไขลิงก์แบบ relative. |

### หมายเหตุ

การระบุ resolver อาจทำให้เกิดช่องโหว่ได้ ใช้ด้วยความระมัดระวัง.

### ดูเพิ่มเติม
* class [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver)
* class [`IParagraphCollection`](/slides/python-net/th/aspose.slides/iparagraphcollection)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)