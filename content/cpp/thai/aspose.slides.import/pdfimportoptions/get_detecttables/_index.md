---
title: get_DetectTables()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าจะตรวจจับตารางหรือไม่เมื่อทำการนำเข้าไฟล์ pdf.
type: docs
weight: 1
url: /th/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const เมธอด


กำหนดว่าตรวจจับตารางหรือไม่เมื่อทำการนำเข้าไฟล์ pdf.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [PdfImportOptions](../)
* เนมสเปซ [Aspose::Slides::Import](../../)
* ไลบรารี [Aspose.Slides](../../../)