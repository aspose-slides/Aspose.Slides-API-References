---
title: GetImage()
second_title: Aspose.Slides برای مرجع API C++
description: یک شیء تصویر بندانگشتی را با مقیاس‌گذاری سفارشی برمی‌گرداند.
type: docs
weight: 144
url: /fa/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) متد

یک شیٔ Thumbnail Image با مقیاس‌گذاری سفارشی برمی‌گرداند.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scaleX | **float** | مقداری که برای مقیاس این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | **float** | مقداری که برای مقیاس این Thumbnail در جهت محور y استفاده می‌شود. |

### مقدار بازگشت

[IImage](../../iimage/) شی.

## یادداشت‌ها

مثال زیر نشان می‌دهد چگونه می‌توان بندانگشتی‌ها را از PowerPoint [Presentation](../../presentation/) تولید کرد:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// دسترسی به اولین اسلاید
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// ایجاد تصویر با مقیاس کامل
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// ذخیره تصویر در دیسک با فرمت JPEG
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
مثال زیر نشان می‌دهد چگونه اسلایدها را به تصویر بیت‌مپ تبدیل کرده و تصاویر را به فرمت PNG ذخیره می‌کنیم:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// اسلاید اول ارائه را به یک شیء Bitmap تبدیل می‌کند
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// تصویر را در قالب PNG ذخیره می‌کند
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
مثال زیر نشان می‌دهد چگونه PowerPoint PPT/PPTX را به JPG تبدیل می‌کنیم:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // ایجاد تصویر با مقیاس کامل
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // ذخیره تصویر در دیسک با فرمت JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
مثال زیر نشان می‌دهد چگونه PowerPoint PPT/PPTX را به JPG با ابعاد سفارشی تبدیل می‌کنیم:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// تعریف ابعاد
int32_t desiredX = 1200;
int32_t desiredY = 800;
// دریافت مقادیر مقیاس‌دار X و Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // ایجاد تصویر با مقیاس کامل
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // ذخیره تصویر در دیسک با فرمت JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() متد

یک شیٔ Thumbnail Image (20٪ اندازه واقعی) برمی‌گرداند.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) متد

یک شیٔ Thumbnail Image با اندازهٔ مشخص برمی‌گرداند.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازهٔ تصویری که باید ایجاد شود. |

### مقدار بازگشت

شی Image.

## یادداشت‌ها

مثال زیر نشان می‌دهد چگونه اسلایدها را به تصاویر با اندازهٔ سفارشی در C# تبدیل می‌کنیم.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// اسلاید اول ارائه را به یک Bitmap با اندازهٔ مشخص تبدیل می‌کند
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// تصویر را در قالب JPEG ذخیره می‌کند
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) متد

یک شیٔ تصویر بندانگشتی tiff با پارامترهای مشخص برمی‌گرداند.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | گزینه‌های Tiff. |

### مقدار بازگشت

شی Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) متد

یک شیٔ Thumbnail Image برمی‌گرداند.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های Rendering. |

### مقدار بازگشت

شی Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) متد

یک شیٔ Thumbnail Image با مقیاس‌گذاری سفارشی برمی‌گرداند.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های Rendering. |
| scaleX | **float** | مقداری که برای مقیاس این Thumbnail در جهت محور x استفاده می‌شود. |
| scaleY | **float** | مقداری که برای مقیاس این Thumbnail در جهت محور y استفاده می‌شود. |

### مقدار بازگشت

شی Bitmap.

## یادداشت‌ها

مثال زیر نشان می‌دهد چگونه اسلایدها را همراه با یادداشت‌ها و نظرات به [Images](../../images/) تبدیل می‌کنیم با استفاده از C#.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// ایجاد گزینه‌های رندرینگ
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// ایجاد گزینه‌های چیدمان یادداشت‌ها و نظرات
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// موقعیت یادداشت‌ها را در صفحه تنظیم می‌کند
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// موقعیت نظرات را در صفحه تنظیم می‌کند
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// عرض ناحیه خروجی نظرات را تنظیم می‌کند
notesCommentsLayouting->set_CommentsAreaWidth(500);
// رنگ ناحیه نظرات را تنظیم می‌کند
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// تنظیم گزینه‌های چیدمان برای رندرینگ
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// اسلاید اول ارائه را به یک شیء IImage تبدیل می‌کند
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// تصویر را در قالب GIF ذخیره می‌کند
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) متد

یک شیٔ Thumbnail Image با اندازهٔ مشخص برمی‌گرداند.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | گزینه‌های Rendering. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | اندازهٔ تصویری که باید ایجاد شود. |

### مقدار بازگشت

شی Image.

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)