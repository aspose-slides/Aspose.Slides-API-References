---
title: HtmlExternalResolver class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver คลาส

วัตถุ callback ที่ใช้โดยขั้นตอนการนำเข้า HTML เพื่อดึงวัตถุที่อ้างอิง เช่น รูปภาพ.  
การใช้ resolver นี้อาจทำให้เกิดช่องโหว่าเมื่อไฟล์ HTML ที่ผู้ใช้ให้มาจะทำให้ซอฟต์แวร์เซิร์ฟเวอร์ดึงไฟล์ในเครื่องหรือเครือข่าย. ใช้ด้วยความระมัดระวัง. แนะนำว่าไม่ควรระบุ HtmlExternalResolver เลย (จะอ่านเฉพาะวัตถุฝังอยู่) หรือสร้างคลาสย่อยที่ตรวจสอบว่า uri ที่ระบุเป็นค่าที่ถูกต้องหรือไม่.

The HtmlExternalResolver type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Methods

| Method | Description |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/th/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | ค้นหา URI สมบูรณ์จาก URI base และ URI สัมพัทธ์. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/th/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | แมพ URI ไปยังอ็อบเจ็กต์ที่มีทรัพยากรจริง. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.importing`](/slides/python-net/th/aspose.slides.importing)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)