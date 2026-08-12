---
title: get_AccessPermissions()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ประกอบด้วยชุดของแฟล็กที่ระบุว่าการอนุญาตเข้าถึงใดควรได้รับการมอบเมื่อเปิดเอกสารด้วยการเข้าถึงของผู้ใช้ ดู PdfAccessPermissions.
type: docs
weight: 261
url: /th/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() method

ประกอบด้วยชุดของแฟล็กที่ระบุว่าการอนุญาตเข้าถึงใดควรได้รับการมอบเมื่อเปิดเอกสารด้วยการเข้าถึงของผู้ใช้ ดู [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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
* เนมสเปซ [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)