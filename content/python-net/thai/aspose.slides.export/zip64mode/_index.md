---
title: Zip64Mode enumeration
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.export/zip64mode/
---
## การกำหนดค่า Zip64Mode

ระบุว่าเมื่อใดควรใช้ส่วนขยายรูปแบบ ZIP64 สำหรับไฟล์ OpenXML

ประเภท Zip64Mode เปิดเผยสมาชิกต่อไปนี้:

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| :- | :- |
| NEVER | ไม่ใช้ส่วนขยายรูปแบบ ZIP64 |
| IF_NECESSARY | ใช้ส่วนขยายรูปแบบ ZIP64 หากจำเป็น |
| ALWAYS | ใช้ส่วนขยายรูปแบบ ZIP64 เสมอ |


### หมายเหตุ

ไฟล์ OpenXML เป็น ZIP-archive ที่มีขีดจำกัด 4 GB (2^32 bytes) สำหรับขนาดไฟล์ที่ไม่ได้บีบอัด,
            ขนาดไฟล์ที่บีบอัด, และขนาดรวมของไฟล์เก็บ, รวมถึงขีดจำกัด 65,535 (2^16-1) ไฟล์ในไฟล์เก็บ.
            ส่วนขยายรูปแบบ ZIP64 เพิ่มขีดจำกัดเป็น 2^64.


### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)