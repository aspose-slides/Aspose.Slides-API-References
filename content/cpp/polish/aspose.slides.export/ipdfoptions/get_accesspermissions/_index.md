---
title: get_AccessPermissions()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Zawiera zestaw flag określających, które uprawnienia dostępu powinny zostać przyznane, gdy dokument zostanie otwarty z dostępem użytkownika. Zobacz PdfAccessPermissions.
type: docs
weight: 261
url: /pl/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() metoda

Zawiera zestaw flag określających, które uprawnienia dostępu powinny zostać przyznane, gdy dokument zostanie otwarty z dostępem użytkownika. Zobacz [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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
* Klasa [IPdfOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)