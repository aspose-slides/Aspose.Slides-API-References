---
title: get_AccessPermissions()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ประกอบด้วยชุดของแฟล็กที่ระบุว่าการอนุญาตเข้าถึงใดควรให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้ ดู PdfAccessPermissions.
type: docs
weight: 300
url: /th/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() เมธอด

ประกอบด้วยชุดของแฟล็กที่ระบุว่าการอนุญาตเข้าถึงใดควรให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้ ดู [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
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
* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)