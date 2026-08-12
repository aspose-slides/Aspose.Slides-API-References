---
title: set_HideInk()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก.
type: docs
weight: 14
url: /th/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) เมธอด


แสดงหรือซ่อน [Ink](../../../aspose.slides.ink/) องค์ประกอบในเอกสารที่ส่งออก.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## หมายเหตุ


ค่าเริ่มต้นเป็น false. 

ตัวอย่างต่อไปนี้แสดงวิธีการซ่อน [Ink](../../../aspose.slides.ink/) องค์ประกอบในเอกสาร PDF ที่ส่งออก: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## ดูเพิ่มเติม

* คลาส [InkOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)