---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides สำหรับ API ของ C++
description: True เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. เขียน bool.
type: docs
weight: 339
url: /th/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) เมธอด

True เพื่อแปลงเมตาไฟล์ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. เขียน **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## หมายเหตุ

ค่าเริ่มต้นคือ **true**. เอกสาร Pdf สามารถประกอบด้วยกราฟิกแบบเวกเตอร์และภาพแบบราสเตอร์. หาก SaveMetafilesAsPng ถูกตั้งค่าเป็น true แล้วภาพ Metafile ต้นฉบับจะถูกแปลงเป็นรูปแบบ Png และบันทึกลงใน Pdf เป็นภาพราสเตอร์. หาก SaveMetafilesAsPng ถูกตั้งค่าเป็น false แล้ว Metafile ต้นฉบับจะถูกแปลงเป็นกราฟิกเวกเตอร์ของ Pdf. แต่ละวิธีมีข้อดีและข้อเสีย. ตัวอย่างเช่น หาก Metafile ถูกแปลงเป็น PNG แล้วอาจเกิดการสูญเสียคุณภาพบางส่วนขณะปรับขนาดเอกสารที่ได้. หาก Metafile ถูกแปลงเป็นกราฟิกเวกเตอร์ของ Pdf แล้วอาจเกิดปัญหาด้านประสิทธิภาพในเครื่องมือดู Pdf.

## ดูเพิ่มเติม

* คลาส [PdfOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)