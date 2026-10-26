---
title: set_AccessPermissions()
second_title: Aspose.Slides для C++ справочник API
description: Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа с пользовательским доступом. См. PdfAccessPermissions.
type: docs
weight: 274
url: /ru/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) метод


Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа с пользовательским доступом. Смотрите [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
```

## Примечания



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Смотрите также

* Перечисление [PdfAccessPermissions](../../pdfaccesspermissions/)
* Класс [IPdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)