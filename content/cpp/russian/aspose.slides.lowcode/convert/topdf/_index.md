---
title: ToPdf()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует презентацию в PDF.
type: docs
weight: 14
url: /ru/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) метод

Преобразует [Presentation](../../../aspose.slides/presentation/) в PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Путь входной презентации |
| outPath | [System::String](../../../system/string/) | Путь вывода |
## Примечания

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) метод

Преобразует [Presentation](../../../aspose.slides/presentation/) в PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Путь входной презентации |
| outPath | [System::String](../../../system/string/) | Путь вывода |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Параметры вывода PDF |
## Примечания

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) метод

Преобразует [Presentation](../../../aspose.slides/presentation/) в PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Входная презентация |
| outPath | [System::String](../../../system/string/) | Путь вывода |
## Примечания

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) метод

Преобразует [Presentation](../../../aspose.slides/presentation/) в PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Входная презентация |
| outPath | [System::String](../../../system/string/) | Путь вывода |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Параметры вывода PDF |
## Примечания

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Convert](../)
* Класс [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Класс [Presentation](../../../aspose.slides/presentation/)
* Пространство имён [Aspose::Slides::LowCode](../../)
* Библиотека [Aspose.Slides](../../../)