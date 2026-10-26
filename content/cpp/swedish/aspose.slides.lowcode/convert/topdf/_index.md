---
title: ToPdf()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar Presentation till PDF.
type: docs
weight: 14
url: /sv/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) metod

Konverterar [Presentation](../../../aspose.slides/presentation/) till PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Path of the input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
## Anmärkningar

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metod

Konverterar [Presentation](../../../aspose.slides/presentation/) till PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Path of the input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Output PDF options |
## Anmärkningar

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PpdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) metod

Konverterar [Presentation](../../../aspose.slides/presentation/) till PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metod

Konverterar [Presentation](../../../aspose.slides/presentation/) till PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Output PDF options |
## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [Convert](../)
* Klass [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Klass [Presentation](../../../aspose.slides/presentation/)
* Namnrymd [Aspose::Slides::LowCode](../../)
* Bibliotek [Aspose.Slides](../../../)