---
title: set_AccessPermissions()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ประกอบด้วยชุดของแฟล็กที่ระบุว่าการอนุญาตการเข้าถึงใดควรได้รับการให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้ ดู PdfAccessPermissions.
type: docs
weight: 313
url: /th/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) เมธอด

ประกอบด้วยชุดของแฟล็กที่ระบุการเข้าถึงที่ควรให้สิทธิ์เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้ ดู [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## หมายเหตุ

```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## ดูเพิ่มเติม

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* คลาส [PdfOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)