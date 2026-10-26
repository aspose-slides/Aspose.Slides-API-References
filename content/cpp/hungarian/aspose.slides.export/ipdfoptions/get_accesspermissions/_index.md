---
title: get_AccessPermissions()
second_title: Aspose.Slides C++ API-referencia
description: Egy zászlók halmazát tartalmazza, amely meghatározza, hogy mely hozzáférési engedélyeket kell megadni a dokumentum felhasználói hozzáféréssel történő megnyitásakor. Lásd PdfAccessPermissions.
type: docs
weight: 261
url: /hu/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() method


Egy zászlók halmazát tartalmazza, amely meghatározza, hogy mely hozzáférési engedélyeket kell megadni a dokumentum felhasználói hozzáféréssel történő megnyitásakor. Lásd [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)