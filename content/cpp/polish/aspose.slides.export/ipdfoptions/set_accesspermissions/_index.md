---
title: set_AccessPermissions()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument jest otwierany z dostępem użytkownika. Zobacz PdfAccessPermissions.
type: docs
weight: 274
url: /pl/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) method


Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument jest otwierany z dostępem użytkownika. Zobacz [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
```

## Uwagi



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Zobacz też

* Wyliczenie [PdfAccessPermissions](../../pdfaccesspermissions/)
* Klasa [IPdfOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)