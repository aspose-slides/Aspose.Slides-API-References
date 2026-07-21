---
title: get_IncludeOleData()
second_title: Справочник API Aspose.Slides для C++
description: True, чтобы преобразовать все данные OLE из презентации во вложенные файлы в результирующем PDF. Читать bool.
type: docs
weight: 456
url: /ru/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() метод


True, чтобы преобразовать все данные OLE из презентации в вложенные файлы в получаемом PDF. Read **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Примечания


По умолчанию **false**. 

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## См. также

* Класс [PdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)