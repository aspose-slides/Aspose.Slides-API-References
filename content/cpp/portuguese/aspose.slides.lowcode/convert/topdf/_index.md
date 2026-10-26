---
title: ToPdf()
second_title: Referência da API Aspose.Slides para C++
description: Converte Presentation para PDF.
type: docs
weight: 14
url: /pt/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) método


Converte [Presentation](../../../aspose.slides/presentation/) para PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Path of the input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
## Observações




```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) método


Converte [Presentation](../../../aspose.slides/presentation/) para PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Path of the input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Output PDF options |
## Observações




```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) método


Converte [Presentation](../../../aspose.slides/presentation/) para PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
## Observações




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) método


Converte [Presentation](../../../aspose.slides/presentation/) para PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Input presentation |
| outPath | [System::String](../../../system/string/) | Output path |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Output PDF options |
## Observações 




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Convert](../)
* Classe [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Namespace [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)