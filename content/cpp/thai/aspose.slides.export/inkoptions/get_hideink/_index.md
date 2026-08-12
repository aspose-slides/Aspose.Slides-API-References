---
title: get_HideInk()
second_title: Aspose.Slides สำหรับ C++: เอกสารอ้างอิง API
description: แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก.
type: docs
weight: 1
url: /th/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() เมธอด


แสดงหรือซ่อน [Ink](../../../aspose.slides.ink/) องค์ประกอบในเอกสารที่ส่งออก.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## หมายเหตุ


ค่าเริ่มต้นคือ false. 

ตัวอย่างต่อไปแสดงวิธีซ่อน [Ink](../../../aspose.slides.ink/) องค์ประกอบในเอกสาร PDF ที่ส่งออก: 
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