---
title: set_DetectTables()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, следует ли обнаруживать таблицы при импорте PDF-файла.
type: docs
weight: 14
url: /ru/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) метод

Определяет, следует ли обнаруживать таблицы при импорте PDF-файла.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## Примечание

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Класс [PdfImportOptions](../)
* Пространство имён [Aspose::Slides::Import](../../)
* Библиотека [Aspose.Slides](../../../)