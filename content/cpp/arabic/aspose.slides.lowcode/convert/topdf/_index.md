---
title: ToPdf()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بتحويل Presentation إلى PDF.
type: docs
weight: 14
url: /ar/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) طريقة

يقوم بتحويل [Presentation](../../../aspose.slides/presentation/) إلى PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | مسار العرض التقديمي المدخل |
| outPath | [System::String](../../../system/string/) | مسار الإخراج |

## ملاحظات

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) طريقة

يقوم بتحويل [Presentation](../../../aspose.slides/presentation/) إلى PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | مسار العرض التقديمي المدخل |
| outPath | [System::String](../../../system/string/) | مسار الإخراج |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | خيارات PDF للإخراج |

## ملاحظات

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PPdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) طريقة

يقوم بتحويل [Presentation](../../../aspose.slides/presentation/) إلى PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المدخل |
| outPath | [System::String](../../../system/string/) | مسار الإخراج |

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) طريقة

يقوم بتحويل [Presentation](../../../aspose.slides/presentation/) إلى PDF.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المدخل |
| outPath | [System::String](../../../system/string/) | مسار الإخراج |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | خيارات PDF للإخراج |

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [Convert](../)
* فئة [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* فئة [Presentation](../../../aspose.slides/presentation/)
* نطاق [Aspose::Slides::LowCode](../../)
* مكتبة [Aspose.Slides](../../../)