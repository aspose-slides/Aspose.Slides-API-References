---
title: ExternalResourceResolver class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver คลาส

คลาส Callback ใช้เพื่อแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร Html, Svg  
การใช้ resolver นี้อาจทำให้เกิดช่องโหว่เมื่อไฟล์ HTML หรือ SVG ที่ลูกค้าให้มาทำให้ซอฟต์แวร์เซิร์ฟเวอร์เข้าถึงไฟล์ในเครื่องหรือเครือข่าย  
ใช้ด้วยความระมัดระวัง  
แนะนำไม่ระบุ ExternalResourceResolver เลย (จะอ่านเฉพาะออบเจกต์ที่ฝังอยู่) หรือสร้างซับคลาสที่ตรวจสอบว่า uri ที่ระบุเป็นค่าที่ถูกต้องหรือไม่  

ประเภท ExternalResourceResolver เปิดเผยสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/th/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | แก้ไข URI แบบเต็มจาก URI base และ URI เชิงสัมพันธ์ |
| [`get_entity(self, absolute_uri)`](/slides/python-net/th/aspose.slides.importing/externalresourceresolver/get_entity/#str) | แมป URI ไปยังอ็อบเจ็กต์ที่มีทรัพยากรจริง |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides.importing`](/slides/python-net/th/aspose.slides.importing)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)