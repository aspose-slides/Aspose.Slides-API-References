---
title: set_AccessPermissions()
second_title: Aspose.Slides för C++ API-referens
description: Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se PdfAccessPermissions.
type: docs
weight: 313
url: /sv/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) metod


Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## Anmärkningar



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Se även

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Klass [PdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)