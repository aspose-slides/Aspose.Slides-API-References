---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: จริงเพื่อแปลง metafile ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG. เขียนเป็น bool.
type: docs
weight: 300
url: /th/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) เมธอด

จริงเพื่อแปลง metafile ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG เขียนเป็น **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## หมายเหตุ

ค่าเริ่มต้นคือ **true**. เอกสาร Pdf สามารถประกอบด้วยกราฟิกเวคเตอร์และภาพราสเตอร์. หาก SaveMetafilesAsPng ถูกตั้งค่าเป็น true แล้วภาพ Metafile แหล่งจะถูกแปลงเป็นรูปแบบ Png และบันทึกลงใน Pdf เป็นภาพราสเตอร์. หาก SaveMetafilesAsPng ถูกตั้งค่าเป็น false แล้ว Metafile แหล่งจะถูกแปลงเป็นกราฟิกเวคเตอร์ของ Pdf. แต่ละวิธีมีข้อดีและข้อเสีย. เช่น หาก Metafile ถูกแปลงเป็น PNG แล้วอาจเกิดการสูญเสียคุณภาพบางส่วนระหว่างการปรับขนาดเอกสารที่ได้. หาก Metafile ถูกแปลงเป็นกราฟิกเวคเตอร์ของ Pdf แล้วอาจเกิดปัญหาด้านประสิทธิภาพในเครื่องมือดู Pdf. 

## ดูเพิ่มเติม

* คลาส [IPdfOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)