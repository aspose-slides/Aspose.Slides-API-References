---
title: ToPdf()
second_title: Aspose.Slides for C++ API Reference
description: Converts Presentation to PDF.
type: docs
weight: 14
url: /cpp/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf([System::String](../../../system/string/), [System::String](../../../system/string/)) method


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

## See Also

* Class [String](../../../system/string/)
* Class [Convert](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
## Convert::ToPdf([System::String](../../../system/string/), [System::String](../../../system/string/), [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\>) method


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

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Class [Convert](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
## Convert::ToPdf([System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\>, [System::String](../../../system/string/)) method


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
## Convert::ToPdf([System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\>, [System::String](../../../system/string/), [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\>) method


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
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Class [Convert](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
