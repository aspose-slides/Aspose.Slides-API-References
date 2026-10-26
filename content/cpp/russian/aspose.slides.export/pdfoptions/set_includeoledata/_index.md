---
title: set_IncludeOleData()
second_title: Aspose.Slides для C++ API Reference
description: True, чтобы преобразовать все данные OLE из презентации в встроенные файлы в результирующем PDF. Записывается **bool**.
type: docs
weight: 469
url: /ru/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) метод

True to convert all OLE data from the presentation to embedded files in the resulting PDF. Записывается **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## Примечания

Default is **false**. 

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