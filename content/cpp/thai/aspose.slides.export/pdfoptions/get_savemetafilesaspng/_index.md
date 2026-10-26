---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: True เพื่อแปลงเมทาฟายล์ทั้งหมดที่ใช้ในงานนำเสนอให้เป็นภาพ PNG. อ่าน bool.
type: docs
weight: 326
url: /th/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() เมธอด

True เพื่อแปลงเมทาฟายล์ทั้งหมดที่ใช้ในงานนำเสนอให้เป็นภาพ PNG. อ่าน **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## หมายเหตุ

ค่าเริ่มต้นคือ **true**. เอกสาร Pdf สามารถมีกราฟิกเวกเตอร์และภาพแรสเตอร์ได้. หาก SaveMetafilesAsPng ถูกตั้งเป็น true แล้วภาพ Metafile ต้นฉบับจะถูกแปลงเป็นรูปแบบ Png และบันทึกลงใน Pdf เป็นภาพแรสเตอร์. หาก SaveMetafilesAsPng ถูกตั้งเป็น false แล้ว Metafile ต้นฉบับจะถูกแปลงเป็นกราฟิกเวกเตอร์ของ Pdf. แต่ละวิธีมีข้อดีและข้อเสีย. ตัวอย่างเช่น หาก Metafile ถูกแปลงเป็น PNG แล้วอาจเกิดการสูญเสียคุณภาพบางส่วนระหว่างการปรับขนาดของเอกสารที่ได้. หาก Metafile ถูกแปลงเป็นกราฟิกเวกเตอร์ของ Pdf แล้วอาจเกิดปัญหาประสิทธิภาพในเครื่องมือดู Pdf.

## ดูเพิ่มเติม

* คลาส [PdfOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)