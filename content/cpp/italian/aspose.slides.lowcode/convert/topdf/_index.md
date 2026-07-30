---
title: ToPdf()
second_title: Aspose.Slides per C++ Riferimento API
description: Converte Presentation in PDF.
type: docs
weight: 14
url: /it/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) metodo

Converte [Presentation](../../../aspose.slides/presentation/) in PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Percorso della presentazione di input |
| outPath | [System::String](../../../system/string/) | Percorso di output |
## Osservazioni

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metodo

Converte [Presentation](../../../aspose.slides/presentation/) in PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Percorso della presentazione di input |
| outPath | [System::String](../../../system/string/) | Percorso di output |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Opzioni PDF di output |
## Osservazioni

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) metodo

Converte [Presentation](../../../aspose.slides/presentation/) in PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentazione di input |
| outPath | [System::String](../../../system/string/) | Percorso di output |
## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metodo

Converte [Presentation](../../../aspose.slides/presentation/) in PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Presentazione di input |
| outPath | [System::String](../../../system/string/) | Percorso di output |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Opzioni PDF di output |
## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Convert](../)
* Classe [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Spazio dei nomi [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)