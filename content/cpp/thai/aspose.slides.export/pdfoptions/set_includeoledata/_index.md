---
title: set_IncludeOleData()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ที่ฝังไว้ใน PDF ที่สร้างขึ้น เขียน bool.
type: docs
weight: 469
url: /th/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) เมธอด


True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ที่ฝังไว้ใน PDF ที่สร้างขึ้น เขียน **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## หมายเหตุ


ค่าเริ่มต้นคือ **false**. 

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## ดูเพิ่มเติม

* คลาส [PdfOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)