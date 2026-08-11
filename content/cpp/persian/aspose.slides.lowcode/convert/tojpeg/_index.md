---
title: ToJpeg()
second_title: مرجع API Aspose.Slides برای C++
description: ارائهٔ ورودی را به مجموعه‌ای از تصاویر با فرمت JPEG تبدیل می‌کند. اگر نام فایل خروجی به صورت \"myPath/myFilename.jpeg\" داده شود، نتیجه به‌صورت مجموعه‌ای از فایل‌های \"myPath/myFilename_N.jpeg\" ذخیره می‌شود که N شمارهٔ اسلاید است.
type: docs
weight: 40
url: /fa/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) متد

ارائهٔ ورودی را به مجموعه‌ای از تصاویر با فرمت JPEG تبدیل می‌کند. 

اگر نام فایل خروجی به شکل \"myPath/myFilename.jpeg\" داده شود، نتیجه به صورت مجموعه‌ای از فایل‌های \"myPath/myFilename_N.jpeg\" ذخیره می‌شود که N شمارهٔ اسلاید است.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائهٔ ورودی. |
| outputFileName | [System::String](../../../system/string/) | نام فایل خروجی. |

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) متد

ارائهٔ ورودی را به مجموعه‌ای از تصاویر با فرمت JPEG تبدیل می‌کند. 

اگر نام فایل خروجی به شکل \"myPath/myFilename.jpeg\" داده شود، نتیجه به صورت مجموعه‌ای از فایل‌های \"myPath/myFilename_N.jpeg\" ذخیره می‌شود که N شمارهٔ اسلاید است.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائهٔ ورودی |
| outputFileName | [System::String](../../../system/string/) | نام فایل خروجی. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازهٔ هر تصویر تولید شده. |

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) متد

ارائهٔ ورودی را به مجموعه‌ای از تصاویر با فرمت JPEG تبدیل می‌کند. 

اگر نام فایل خروجی به شکل \"myPath/myFilename.jpeg\" داده شود، نتیجه به صورت مجموعه‌ای از فایل‌های \"myPath/myFilename_N.jpeg\" ذخیره می‌شود که N شمارهٔ اسلاید است.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائهٔ ورودی. |
| outputFileName | [System::String](../../../system/string/) | نام فایل خروجی. |
| scale | **float** | عامل مقیاس‌بندی اعمال‌شده بر تصاویر خروجی نسبت به اندازهٔ اصلی اسلاید. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های رندرینگ. |

## توضیحات

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* کلاس [String](../../../system/string/)
* کلاس [Convert](../)
* کلاس [Size](../../../system.drawing/size/)
* کلاس [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* فضای‌نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)