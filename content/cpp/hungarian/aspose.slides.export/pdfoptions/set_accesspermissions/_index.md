---
title: set_AccessPermissions()
second_title: Aspose.Slides C++ API-referencia
description: Tartalmaz egy jelzőkészletet, amely meghatározza, hogy milyen hozzáférési engedélyeket kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd PdfAccessPermissions.
type: docs
weight: 313
url: /hu/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) metódus

Tartalmaz egy jelzőkészletet, amely meghatározza, hogy mely hozzáférési engedélyeket kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## Megjegyzések

```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Lásd még

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Osztály [PdfOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)