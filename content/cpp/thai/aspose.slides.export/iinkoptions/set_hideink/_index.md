---
title: set_HideInk()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก.
type: docs
weight: 14
url: /th/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) เมธอด


แสดงหรือซ่อนองค์ประกอบ [Ink](../../../aspose.slides.ink/) ในเอกสารที่ส่งออก.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## หมายเหตุ


ค่าเริ่มต้นเป็น false. 

ตัวอย่างต่อไปนี้แสดงวิธีซ่อนองค์ประกอบ [Ink](../../../aspose.slides.ink/) ในเอกสาร PDF ที่ส่งออก: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## ดูเพิ่มเติม

* คลาส [IInkOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)