---
title: save_metafiles_as_png property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png คุณสมบัติ
True เพื่อแปลง metafiles ทั้งหมดที่ใช้ในงานนำเสนอเป็นภาพ PNG.
            อ่าน/เขียน **bool**.


### หมายเหตุ

ค่าเริ่มต้นคือ **true** .
            เอกสาร Pdf สามารถมีกราฟิกเวกเตอร์และภาพแรสเตอร์ได้. 
            หาก SaveMetafilesAsPng ถูกตั้งค่าเป็น true แล้วภาพ Metafile ต้นฉบับจะถูกแปลงเป็นรูปแบบ Png และบันทึกลงใน Pdf เป็นภาพแรสเตอร์. หาก SaveMetafilesAsPng ถูกตั้งค่าเป็น false แล้ว Metafile ต้นฉบับจะถูกแปลงเป็นกราฟิกเวกเตอร์ Pdf. แต่ละวิธีมีข้อดีและข้อเสีย. ตัวอย่างเช่น หาก Metafile ถูกแปลงเป็น PNG จะอาจเกิดการสูญเสียคุณภาพบางส่วนเมื่อทำการขยายเอกสารที่ได้. หาก Metafile ถูกแปลงเป็นกราฟิกเวกเตอร์ Pdf แล้วอาจเกิดปัญหาด้านประสิทธิภาพในเครื่องมือดู Pdf.

### คำนิยาม:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```


### ดูเพิ่มเติม
* คลาส [`IPdfOptions`](/slides/python-net/th/aspose.slides.export/ipdfoptions)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)