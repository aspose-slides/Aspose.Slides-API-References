---
title: get_DetectTables()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, следует ли обнаруживать таблицы при импорте PDF-файла.
type: docs
weight: 1
url: /ru/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const метод

Определяет, следует ли обнаруживать таблицы при импорте PDF-файла.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [PdfImportOptions](../)
* Пространство имен [Aspose::Slides::Import](../../)
* Библиотека [Aspose.Slides](../../../)