---
title: ToPdf()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die Präsentation in PDF.
type: docs
weight: 14
url: /de/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) Methode


Konvertiert [Presentation](../../../aspose.slides/presentation/) in PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Pfad der Eingabepräsentation |
| outPath | [System::String](../../../system/string/) | Ausgabepfad |
## Bemerkungen




```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) Methode


Konvertiert [Presentation](../../../aspose.slides/presentation/) in PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Pfad der Eingabepräsentation |
| outPath | [System::String](../../../system/string/) | Ausgabepfad |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | PDF-Ausgaboptionen |
## Bemerkungen 




```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) Methode


Konvertiert [Presentation](../../../aspose.slides/presentation/) in PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Eingabepräsentation |
| outPath | [System::String](../../../system/string/) | Ausgabepfad |
## Bemerkungen 




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) Methode


Konvertiert [Presentation](../../../aspose.slides/presentation/) in PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Eingabepräsentation |
| outPath | [System::String](../../../system/string/) | Ausgabepfad |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | PDF-Ausgaboptionen |
## Bemerkungen 




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Convert](../)
* Klasse [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Namensraum [Aspose::Slides::LowCode](../../)
* Bibliothek [Aspose.Slides](../../../)