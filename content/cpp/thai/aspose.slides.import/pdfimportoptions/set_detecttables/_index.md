---
title: set_DetectTables()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: กำหนดว่าจะแยกตารางเมื่อทำการนำเข้าไฟล์ pdf หรือไม่.
type: docs
weight: 14
url: /th/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) เมธอด


กำหนดว่าจะแยกตารางเมื่อทำการนำเข้าไฟล์ pdf หรือไม่.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
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