---
title: ToPdf()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει Presentation σε PDF.
type: docs
weight: 14
url: /el/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) μέθοδος

Μετατρέπει [Presentation](../../../aspose.slides/presentation/) σε PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Διαδρομή της εισαγόμενης παρουσίασης |
| outPath | [System::String](../../../system/string/) | Διαδρομή εξόδου |

## Παρατηρήσεις

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) μέθοδος

Μετατρέπει [Presentation](../../../aspose.slides/presentation/) σε PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Διαδρομή της εισαγόμενης παρουσίασης |
| outPath | [System::String](../../../system/string/) | Διαδρομή εξόδου |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Επιλογές PDF εξόδου |

## Παρατηρήσεις

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PPdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) μέθοδος

Μετατρέπει [Presentation](../../../aspose.slides/presentation/) σε PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Παρουσίαση εισόδου |
| outPath | [System::String](../../../system/string/) | Διαδρομή εξόδου |

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) μέθοδος

Μετατρέπει [Presentation](../../../aspose.slides/presentation/) σε PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Παρουσίαση εισόδου |
| outPath | [System::String](../../../system/string/) | Διαδρομή εξόδου |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | Επιλογές PDF εξόδου |

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Convert](../)
* Κλάση [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* Κλάση [Presentation](../../../aspose.slides/presentation/)
* Χώρος ονομάτων [Aspose::Slides::LowCode](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)