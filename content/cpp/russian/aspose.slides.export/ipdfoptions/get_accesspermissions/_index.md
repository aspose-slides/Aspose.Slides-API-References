---
title: get_AccessPermissions()
second_title: Aspose.Slides для C++ справочник API
description: Содержит набор флагов, указывающих, какие разрешения доступа следует предоставить при открытии документа с пользовательским доступом. См. PdfAccessPermissions.
type: docs
weight: 261
url: /ru/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() метод

Содержит набор флагов, указывающих, какие разрешения доступа следует предоставить при открытии документа с пользовательским доступом. См. [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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
* Класс [IPdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)