---
title: get_IncludeOleData()
second_title: อ้างอิง API ของ Aspose.Slides for C++
description: True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้ผลลัพธ์. อ่าน bool.
type: docs
weight: 456
url: /th/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() เมธอด

True เพื่อแปลงข้อมูล OLE ทั้งหมดจากงานนำเสนอเป็นไฟล์ฝังใน PDF ที่ได้ผลลัพธ์. อ่าน **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
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