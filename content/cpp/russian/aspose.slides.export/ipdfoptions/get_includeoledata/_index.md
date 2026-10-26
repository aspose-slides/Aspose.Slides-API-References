---
title: get_IncludeOleData()
second_title: Справочник API Aspose.Slides для C++
description: True — преобразовать все данные OLE из презентации во вложенные файлы в результирующем PDF. Чтение bool.
type: docs
weight: 456
url: /ru/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() метод


True — преобразовать все данные OLE из презентации во вложенные файлы в результирующем PDF. Чтение **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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

* Класс [IPdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)