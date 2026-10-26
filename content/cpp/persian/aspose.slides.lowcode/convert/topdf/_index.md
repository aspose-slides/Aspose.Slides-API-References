---
title: ToPdf()
second_title: مرجع API Aspose.Slides برای C++
description: Presentation را به PDF تبدیل می‌کند.
type: docs
weight: 14
url: /fa/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) متد

[Presentation](../../../aspose.slides/presentation/) را به PDF تبدیل می‌کند.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | مسیر ارائه ورودی |
| outPath | [System::String](../../../system/string/) | مسیر خروجی |
## توضیحات

```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) متد

[Presentation](../../../aspose.slides/presentation/) را به PDF تبدیل می‌کند.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | مسیر ارائه ورودی |
| outPath | [System::String](../../../system/string/) | مسیر خروجی |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | گزینه‌های PDF خروجی |
## توضیحات

```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) متد

[Presentation](../../../aspose.slides/presentation/) را به PDF تبدیل می‌کند.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائه ورودی |
| outPath | [System::String](../../../system/string/) | مسیر خروجی |
## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) متد

[Presentation](../../../aspose.slides/presentation/) را به PDF تبدیل می‌کند.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائه ورودی |
| outPath | [System::String](../../../system/string/) | مسیر خروجی |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | گزینه‌های PDF خروجی |
## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## موارد مرتبط

* نوع تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [Convert](../)
* کلاس [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* فضای‌نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)