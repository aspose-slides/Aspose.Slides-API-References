---
title: jpeg_quality property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## jpeg_quality คุณสมบัติ
คืนค่า หรือ ตั้งค่าค่าที่กำหนดคุณภาพของภาพ JPEG ภายในเอกสาร PDF.
อ่าน/เขียน **int**.

### หมายเหตุ

มีผลเฉพาะเมื่อเอกสารมีภาพ JPEG อยู่.

ใช้คุณสมบัตินี้เพื่อรับหรือกำหนดคุณภาพของภาพภายในเอกสารเมื่อบันทึกเป็นรูปแบบ PDF.
ค่าจะอยู่ในช่วงตั้งแต่ 0 ถึง 100 โดยที่ 0 หมายถึงคุณภาพแย่ที่สุดแต่การบีบอัดสูงสุดและ 100 หมายถึงคุณภาพดีที่สุดแต่การบีบอัดต่ำสุด.

ค่าเริ่มต้นคือ **95** .

### คำกำหนด:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IHtmlOptions`](/slides/python-net/th/aspose.slides.export/ihtmloptions)
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)