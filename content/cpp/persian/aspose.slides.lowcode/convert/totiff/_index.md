---
title: ToTiff()
second_title: Aspose.Slides برای C++ مرجع API
description: ارائه ورودی را به مجموعه‌ای از تصاویر با فرمت TIFF تبدیل می‌کند. اگر نام فایل خروجی به صورت \"myPath/myFilename.tiff\" باشد، نتیجه به‌صورت مجموعه‌ای از فایل‌های \"myPath/myFilename_N.tiff\" ذخیره می‌شود که N شماره اسلاید است.
type: docs
weight: 66
url: /fa/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) متد


پیشنهاد ورودی را به مجموعه‌ای از تصاویر با فرمت TIFF تبدیل می‌کند. 

اگر نام فایل خروجی به صورت \"myPath/myFilename.tiff\" داده شود، نتیجه به‌صورت مجموعه‌ای از فایل‌های \"myPath/myFilename_N.tiff\" ذخیره می‌شود که N شماره اسلاید است.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائه ورودی. |
| outputFileName | [System::String](../../../system/string/) | نام فایل خروجی. |
## توضیحات




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) متد


ارائه ورودی را به فرمت TIFF با گزینه‌های سفارشی تبدیل می‌کند. اگر نام فایل خروجی به صورت \"myPath/myFilename.tiff\" باشد و *multipage* **false** باشد، نتیجه به‌صورت مجموعه‌ای از فایل‌های \"myPath/myFilename_N.tiff\" ذخیره می‌شود که N شماره اسلاید است. در غیر این صورت، اگر *multipage* **true** باشد، نتیجه یک سند چندصفحه \"myPath/myFilename.tiff\" خواهد بود.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائه ورودی. |
| outputFileName | [System::String](../../../system/string/) | نام فایل خروجی. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | گزینه‌های ذخیره‌سازی TIFF. |
| multipage | **bool** | مشخص می‌کند که آیا سند TIFF تولید شده باید چندصفحه باشد یا نه. |
## توضیحات




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* کلاس [String](../../../system/string/)
* کلاس [Convert](../)
* کلاس [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* فضای‌نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)