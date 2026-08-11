---
title: ToPng()
second_title: Aspose.Slides برای C++ مرجع API
description: ارائه ورودی را به مجموعه‌ای از تصاویر با فرمت PNG تبدیل می‌کند.  اگر نام فایل خروجی به صورت \"myPath/myFilename.png\" داده شود، نتیجه به‌صورت مجموعه‌ای از فایل‌های \"myPath/myFilename_N.png\" ذخیره می‌شود که در آن N شماره اسلاید است.
type: docs
weight: 53
url: /fa/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) method

تبدیل ارائه ورودی به مجموعه‌ای از تصاویر با فرمت PNG.

اگر نام فایل خروجی به صورت "myPath/myFilename.png" داده شود، نتیجه به صورت مجموعه‌ای از فایل‌های "myPath/myFilename_N.png" ذخیره می‌شود که در آن N شماره اسلاید است.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائه ورودی. |
| outputFileName | [System::String](../../../system/string/) | نام فایل خروجی. |
## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) method

تبدیل ارائه ورودی به مجموعه‌ای از تصاویر با فرمت PNG.

اگر نام فایل خروجی به صورت "myPath/myFilename.png" داده شود، نتیجه به صورت مجموعه‌ای از فایل‌های "myPath/myFilename_N.png" ذخیره می‌شود که در آن N شماره اسلاید است.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائه ورودی |
| outputFileName | [System::String](../../../system/string/) | نام فایل خروجی. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازه هر تصویر تولید شده. |
## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) method

تبدیل ارائه ورودی به مجموعه‌ای از تصاویر با فرمت PNG.

اگر نام فایل خروجی به صورت "myPath/myFilename.png" داده شود، نتیجه به صورت مجموعه‌ای از فایل‌های "myPath/myFilename_N.png" ذخیره می‌شود که در آن N شماره اسلاید است.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائه ورودی. |
| outputFileName | [System::String](../../../system/string/) | نام فایل خروجی. |
| scale | **float** | عامل مقیاس‌دهی اعمال‌شده بر تصاویر خروجی نسبت به اندازه اسلاید اصلی. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |
## ملاحظات

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## مراجع مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* کلاس [String](../../../system/string/)
* کلاس [Convert](../)
* کلاس [Size](../../../system.drawing/size/)
* کلاس [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* فضای‌نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)