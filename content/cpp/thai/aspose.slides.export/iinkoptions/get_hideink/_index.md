---
title: get_HideInk()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก
type: docs
weight: 1
url: /th/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() เมธอด

แสดงหรือซ่อน [Ink](../../../aspose.slides.ink/) องค์ประกอบในเอกสารที่ส่งออก.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## หมายเหตุ

ค่าเริ่มต้นคือ false. 

ตัวอย่างต่อไปนี้แสดงวิธีซ่อน [Ink](../../../aspose.slides.ink/) องค์ประกอบในเอกสาร PDF ที่ส่งออก: 
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