---
title: GetImage()
second_title: مرجع API Aspose.Slides للغة C++
description: يرجع كائن صورة مصغرة مع تحجيم مخصص.
type: docs
weight: 144
url: /ar/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) طريقة

يرجع كائن صورة مصغرة مع تحجيم مخصص.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| scaleX | **float** | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه محور x. |
| scaleY | **float** | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه محور y. |

### قيمة الإرجاع

[IImage](../../iimage/) كائن.

## ملاحظات

المثال التالي يوضح كيفية إنشاء صور مصغرة من PowerPoint [Presentation](../../presentation/):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
المثال التالي يوضح كيفية تحويل الشرائح إلى بتّامب وحفظ الصور بصيغة PNG:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// يحول الشريحة الأولى في العرض التقديمي إلى كائن Bitmap object
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// يحفظ الصورة بصيغة PNG
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
المثال التالي يوضح كيفية تحويل PowerPoint PPT/PPTX إلى JPG:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // إنشاء صورة بحجم كامل
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // احفظ الصورة على القرص بصيغة JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
المثال التالي يوضح كيفية تحويل PowerPoint PPT/PPTX إلى JPG بأبعاد مخصصة:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// تعريف الأبعاد
int32_t desiredX = 1200;
int32_t desiredY = 800;
// الحصول على القيم المقاسة لـ X و Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // إنشاء صورة بحجم كامل
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // حفظ الصورة على القرص بصيغة JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() طريقة

يرجع كائن صورة مصغرة (20% من الحجم الحقيقي).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) طريقة

يرجع كائن صورة مصغرة بحجم محدد.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم الصورة التي سيتم إنشاؤها. |

### قيمة الإرجاع

كائن صورة.

## ملاحظات

المثال التالي يوضح كيفية تحويل الشرائح إلى صور بأحجام مخصصة باستخدام C#.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// يحول الشريحة الأولى في العرض التقديمي إلى كائن Bitmap بالحجم المحدد
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// يحفظ الصورة بصيغة JPEG
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) طريقة

يرجع كائن صورة tiff مصغرة مع معلمات محددة.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | خيارات Tiff. |

### قيمة الإرجاع

كائن صورة.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) طريقة

يرجع كائن صورة مصغرة.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات العرض. |

### قيمة الإرجاع

كائن صورة.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) طريقة

يرجع كائن صورة مصغرة مع تحجيم مخصص.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات العرض. |
| scaleX | **float** | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه محور x. |
| scaleY | **float** | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه محور y. |

### قيمة الإرجاع

كائنات Bitmap.

## ملاحظات

المثال التالي يوضح كيفية تحويل الشرائح مع الملاحظات والتعليقات إلى [Images](../../images/) باستخدام C#.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// إنشاء خيارات العرض
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// إنشاء خيارات تنسيق الملاحظات والتعليقات
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// يضبط موضع الملاحظات على الصفحة
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// يضبط موضع التعليقات على الصفحة
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// يضبط عرض منطقة إخراج التعليقات
notesCommentsLayouting->set_CommentsAreaWidth(500);
// يضبط لون منطقة التعليقات
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// ضبط خيارات التخطيط للعرض
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// يحول الشريحة الأولى في العرض التقديمي إلى كائن IImage object
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// يحفظ الصورة بصيغة GIF
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) طريقة

يرجع كائن صورة مصغرة بحجم محدد.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات العرض. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم الصورة التي سيتم إنشاؤها. |

### قيمة الإرجاع

كائن صورة.

## أنظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IImage](../../iimage/)
* فئة [Slide](../)
* فئة [Size](../../../system.drawing/size/)
* فئة [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* فئة [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)