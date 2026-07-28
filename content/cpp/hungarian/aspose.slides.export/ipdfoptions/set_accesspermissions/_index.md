---
title: set_AccessPermissions()
second_title: Aspose.Slides C++ API referencia
description: A dokumentum felhasználói hozzáféréssel történő megnyitásakor megadandó hozzáférési engedélyeket meghatározó jelzőkészletet tartalmaz. Lásd PdfAccessPermissions.
type: docs
weight: 274
url: /hu/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) metódus

Tartalmaz egy jelzőkészletet, amely meghatározza, hogy milyen hozzáférési engedélyeket kell megadni, amikor a dokumentumot felhasználói hozzáféréssel nyitják meg. Lásd [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
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
* Osztály [IPdfOptions](../)
* Névtere [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)