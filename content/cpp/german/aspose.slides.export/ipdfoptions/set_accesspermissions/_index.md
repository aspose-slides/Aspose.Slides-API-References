---
title: set_AccessPermissions()
second_title: Aspose.Slides für C++ API-Referenz
description: Enthält eine Menge von Flags, die festlegen, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzernutzung geöffnet wird. Siehe PdfAccessPermissions.
type: docs
weight: 274
url: /de/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) Methode


Enthält eine Menge von Flags, die festlegen, welche Zugriffsberechtigungen gewährt werden sollen, wenn das Dokument mit Benutzernutzung geöffnet wird. Siehe [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
```

## Hinweise



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Siehe auch

* Aufzählung [PdfAccessPermissions](../../pdfaccesspermissions/)
* Klasse [IPdfOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)