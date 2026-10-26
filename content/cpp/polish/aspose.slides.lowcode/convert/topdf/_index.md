---
title: ToPdf()
second_title: Aspose.Slides dla C++ API Reference
description: Konwertuje prezentację do formatu PDF.
type: docs
weight: 14
url: /pl/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) metoda

Konwertuje [Presentation](../../../aspose.slides/presentation/) do PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Ścieżka prezentacji wejściowej |
| outPath | [System::String](../../../system/string/) | Ścieżka wyjściowa |

## Uwagi

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metoda

Konwertuje [Presentation](../../../aspose.slides/presentation/) do PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Ścieżka prezentacji wejściowej |
| outPath | [System::String](../../../system/string/) | Ścieżka wyjściowa |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Opcje wyjściowego PDF |

## Uwagi

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PPdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) metoda

Konwertuje [Presentation](../../../aspose.slides/presentation/) do PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Prezentacja wejściowa |
| outPath | [System::String](../../../system/string/) | Ścieżka wyjściowa |

## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metoda

Konwertuje [Presentation](../../../aspose.slides/presentation/) do PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Prezentacja wejściowa |
| outPath | [System::String](../../../system/string/) | Ścieżka wyjściowa |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Opcje wyjściowego PDF |

## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [Convert](../)
* Klasa [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Klasa [Presentation](../../../aspose.slides/presentation/)
* Przestrzeń nazw [Aspose::Slides::LowCode](../../)
* Biblioteka [Aspose.Slides](../../../)