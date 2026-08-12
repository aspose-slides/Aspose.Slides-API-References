---
title: set_AccessPermissions()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: มีชุดของแฟล็กที่ระบุว่าการอนุญาตการเข้าถึงใดบ้างควรให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้ ดู PdfAccessPermissions.
type: docs
weight: 274
url: /th/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) เมธอด


มีชุดของแฟล็กที่ระบุว่าการอนุญาตการเข้าถึงใดบ้างควรให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้ ดู [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
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
* คลาส [IPdfOptions](../)
* เนมส페ซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)