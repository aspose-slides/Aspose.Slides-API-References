---
title: add_from_html method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
เพิ่มข้อความจากสตริง HTML ที่ระบุลงในคอลเลกชัน


```python
def add_from_html(self, text):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| text | **str** | ข้อความ HTML. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
เพิ่มข้อความจากสตริง HTML ที่ระบุลงในคอลเลกชัน


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| text | **str** | ข้อความ HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver) | อ็อบเจ็กต์ callback Resolver ที่ทำการแก้ไข URIs และดึงอ็อบเจ็กต์ที่อ้างอิง |
| uri | **str** | URI สำหรับการเพิ่มเอกสาร HTML ใช้สำหรับแก้ไขลิงก์แบบสัมพันธ์ |

### หมายเหตุ

การระบุ resolver อาจทำให้เกิดช่องโหว่ได้ ใช้งานด้วยความระมัดระวัง



### ดูเพิ่มเติม
* คลาส [`IExternalResourceResolver`](/slides/python-net/th/aspose.slides.importing/iexternalresourceresolver)
* คลาส [`ParagraphCollection`](/slides/python-net/th/aspose.slides/paragraphcollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)