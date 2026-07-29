---
title: set_AccessPermissions()
second_title: Aspose.Slides för C++ API-referens
description: Innehåller en uppsättning flaggor som anger vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se PdfAccessPermissions.
type: docs
weight: 274
url: /sv/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) metod


Innehåller en uppsättning flaggor som anger vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
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
* Klass [IPdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)