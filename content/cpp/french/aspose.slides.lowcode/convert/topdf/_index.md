---
title: ToPdf()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la présentation en PDF.
type: docs
weight: 14
url: /fr/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) méthode

Convertit [Presentation](../../../aspose.slides/presentation/) en PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Chemin de la présentation d'entrée |
| outPath | [System::String](../../../system/string/) | Chemin de sortie |
## Remarques

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) méthode

Convertit [Presentation](../../../aspose.slides/presentation/) en PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Chemin de la présentation d'entrée |
| outPath | [System::String](../../../system/string/) | Chemin de sortie |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Options PDF de sortie |
## Remarques

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) méthode

Convertit [Presentation](../../../aspose.slides/presentation/) en PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Présentation d'entrée |
| outPath | [System::String](../../../system/string/) | Chemin de sortie |
## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) méthode

Convertit [Presentation](../../../aspose.slides/presentation/) en PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Présentation d'entrée |
| outPath | [System::String](../../../system/string/) | Chemin de sortie |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Options PDF de sortie |
## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Convert](../)
* Classe [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Espace de noms [Aspose::Slides::LowCode](../../)
* Bibliothèque [Aspose.Slides](../../../)