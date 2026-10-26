---
title: set_AccessPermissions()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument zostanie otwarty z dostępem użytkownika. Zobacz PdfAccessPermissions.
type: docs
weight: 313
url: /pl/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) metoda

Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument zostanie otwarty z dostępem użytkownika. Zobacz [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## Uwagi

```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Zobacz także

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)