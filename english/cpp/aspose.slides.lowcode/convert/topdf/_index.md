---
title: ToPdf()
second_title: Aspose.Slides for C++ API Reference
description: Converts Presentation to PDF.
type: docs
weight: 14
url: /cpp/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) method


Converts [Presentation](../../../aspose.slides/presentation/) to PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Path of the input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
## Remarks




```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) method


Converts [Presentation](../../../aspose.slides/presentation/) to PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Path of the input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Output PDF options |
## Remarks




```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) method


Converts [Presentation](../../../aspose.slides/presentation/) to PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) method


Converts [Presentation](../../../aspose.slides/presentation/) to PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Output PDF options |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)