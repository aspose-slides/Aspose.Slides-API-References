---
title: CompressImage()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. بشكل اختياري، يقوم أيضًا بحذف المناطق المقصوصة.
type: docs
weight: 443
url: /ar/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) طريقة

يقوم بضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. بشكل اختياري، يقوم أيضًا بحذف المناطق المقصوصة.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | إذا كان true، فإن الطريقة ستزيل المناطق المقصوصة من الصورة، مما قد يقلل حجمها أكثر. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | دقة الهدف للضغط، محددة كقيمة لتعداد [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### قيمة الإرجاع

قيمة **bool** تشير إلى ما إذا كانت الصورة قد تم ضغطها بنجاح. تُعيد ****true****

## ملاحظات

تغيّر هذه الطريقة حجم الصورة ودقتها بشكل مشابه لميزة "Picture Format -> Compress Pictures" في PowerPoint.

إذا تم تغيير حجم الصورة أو قصها، وإلا ****false****.

المثال التالي يوضح كيفية استخدام طريقة **CompressImage** لتقليل حجم صورة في عرض تقديمي عن طريق ضبط دقة الهدف وإزالة المناطق المقصوصة: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// ضغط الصورة بدقة هدف 150 DPI (دقة الويب) وإزالة المناطق المقصوصة
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) طريقة

يقوم بضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. بشكل اختياري، يقوم أيضًا بحذف المناطق المقصوصة.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | إذا كان true، فإن الطريقة ستزيل المناطق المقصوصة من الصورة، مما قد يقلل حجمها أكثر. |
| resolution | **float** | دقة الهدف بوحدة DPI. يجب أن تكون هذه القيمة موجبة وتحدد كيفية تغيير حجم الصورة. |

### قيمة الإرجاع

قيمة **bool** تشير إلى ما إذا كانت الصورة قد تم ضغطها بنجاح. تُعيد ****true****

## ملاحظات

تغيّر هذه الطريقة حجم الصورة ودقتها بشكل مشابه لميزة "Picture Format -> Compress Pictures" في PowerPoint.

إذا تم تغيير حجم الصورة أو قصها، وإلا ****false****.

المثال التالي يوضح كيفية استخدام طريقة **CompressImage** لتقليل حجم صورة في عرض تقديمي عن طريق ضبط دقة الهدف وإزالة المناطق المقصوصة: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// ضغط الصورة بدقة هدف 150 DPI (دقة الويب) وإزالة المناطق المقصوصة
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // دقة الويب
```

## انظر أيضًا

* تعداد [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* فئة [PictureFillFormat](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)