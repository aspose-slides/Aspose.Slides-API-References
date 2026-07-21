---
title: set_AccessPermissions()
second_title: Справочник API Aspose.Slides для C++
description: Содержит набор флагов, определяющих, какие разрешения доступа должны быть предоставлены при открытии документа с пользовательским доступом. См. PdfAccessPermissions.
type: docs
weight: 313
url: /ru/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) метод

Содержит набор флагов, определяющих, какие разрешения доступа должны быть предоставлены при открытии документа с пользовательским доступом. См. [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## Примечания

```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## См. также

* Перечисление [PdfAccessPermissions](../../pdfaccesspermissions/)
* Класс [PdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)