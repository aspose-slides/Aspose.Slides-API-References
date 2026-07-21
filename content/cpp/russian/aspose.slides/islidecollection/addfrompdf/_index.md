---
title: AddFromPdf()
second_title: Aspose.Slides для C++ справочник API
description: Создает слайды из PDF-документа и добавляет их в конец коллекции.
type: docs
weight: 131
url: /ru/aspose.slides/islidecollection/addfrompdf/
---
## ISlideCollection::AddFromPdf(System::String) метод

Создает слайды из PDF-документа и добавляет их в конец коллекции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Путь к PDF-документу |

### Возвращаемое значение

Добавленные слайды

## Примечания



Пример: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## ISlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) метод

Создает слайды из PDF-документа и добавляет их в конец коллекции, учитывая параметры импорта pdf.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Путь к PDF-документу |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Параметры импорта pdf |

### Возвращаемое значение

Добавленные слайды

## Примечания



Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) метод

Создает слайды из PDF-документа и добавляет их в конец коллекции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, используемый в качестве источника PDF-документа |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Параметры импорта pdf |

### Возвращаемое значение

Добавленные слайды

## Примечания



Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// установить обнаружение таблиц
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) метод

Создает слайды из PDF-документа и добавляет их в конец коллекции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, используемый в качестве источника PDF-документа |

### Возвращаемое значение

Добавленные слайды

## Примечания



Пример: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISlide](../../islide/)
* Класс [String](../../../system/string/)
* Класс [ISlideCollection](../)
* Класс [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Класс [Stream](../../../system.io/stream/)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)