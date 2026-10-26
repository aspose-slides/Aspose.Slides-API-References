---
title: ToPdf()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte Presentation a PDF.
type: docs
weight: 14
url: /es/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) método

Convierte [Presentation](../../../aspose.slides/presentation/) a PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Path of the input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
## Observaciones

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) método

Convierte [Presentation](../../../aspose.slides/presentation/) a PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Path of the input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Output PDF options |
## Observaciones

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) método

Convierte [Presentation](../../../aspose.slides/presentation/) a PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) método

Convierte [Presentation](../../../aspose.slides/presentation/) a PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Output PDF options |
## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [Convert](../)
* Clase [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Clase [Presentation](../../../aspose.slides/presentation/)
* Espacio de nombres [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)