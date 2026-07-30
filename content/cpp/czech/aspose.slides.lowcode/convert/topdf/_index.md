---
title: ToPdf()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Převádí prezentaci do PDF.
type: docs
weight: 14
url: /cs/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) metoda

Převádí [Presentation](../../../aspose.slides/presentation/) do PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Cesta k vstupní prezentaci |
| outPath | [System::String](../../../system/string/) | Výstupní cesta |

## Poznámky

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metoda

Převádí [Presentation](../../../aspose.slides/presentation/) do PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Cesta k vstupní prezentaci |
| outPath | [System::String](../../../system/string/) | Výstupní cesta |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Možnosti výstupního PDF |

## Poznámky

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) metoda

Převádí [Presentation](../../../aspose.slides/presentation/) do PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Vstupní prezentace |
| outPath | [System::String](../../../system/string/) | Výstupní cesta |

## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) metoda

Převádí [Presentation](../../../aspose.slides/presentation/) do PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Vstupní prezentace |
| outPath | [System::String](../../../system/string/) | Výstupní cesta |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Možnosti výstupního PDF |

## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [Convert](../)
* Třída [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Třída [Presentation](../../../aspose.slides/presentation/)
* Jmenný prostor [Aspose::Slides::LowCode](../../)
* Knihovna [Aspose.Slides](../../../)