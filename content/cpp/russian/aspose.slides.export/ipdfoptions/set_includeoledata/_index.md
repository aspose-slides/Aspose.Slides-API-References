---
title: set_IncludeOleData()
second_title: Справочник API Aspose.Slides для C++
description: True, чтобы конвертировать все данные OLE из презентации в встроенные файлы в результирующем PDF. Записать bool.
type: docs
weight: 469
url: /ru/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## метод IPdfOptions::set_IncludeOleData(bool)

True, чтобы конвертировать все данные OLE из презентации в встроенные файлы в получаемом PDF. Записать **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
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

## Смотрите тоже

* Класс [IPdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)