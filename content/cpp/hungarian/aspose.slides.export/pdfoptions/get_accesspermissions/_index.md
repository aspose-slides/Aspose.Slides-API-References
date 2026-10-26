---
title: get_AccessPermissions()
second_title: Aspose.Slides C++ API referenciája
description: Tartalmaz egy zászlóhalmazt, amely meghatározza, hogy mely hozzáférési engedélyeket kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd PdfAccessPermissions.
type: docs
weight: 300
url: /hu/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() metódus


Tartalmaz egy zászlóhalmazt, amely meghatározza, hogy mely hozzáférési engedélyeket kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
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
* Library [Aspose.Slides](../../../)