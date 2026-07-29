---
title: get_AccessPermissions()
second_title: Aspose.Slides för C++ API-referens
description: Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se PdfAccessPermissions.
type: docs
weight: 261
url: /sv/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() metod

Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
```

## Anmärkningar

```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Se också

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Klass [IPdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)