---
title: CompressImage()
second_title: مرجع Aspose.Slides للغة C++ API
description: يقوم بضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. يمكن أيضًا حذف المناطق المقصوصة اختياريًا.
type: docs
weight: 443
url: /ar/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) طريقة

يقوم بضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. اختياريًا، يحذف أيضًا المناطق المقصوصة.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | إذا كان true، ستزيل الطريقة المناطق المقصوصة من الصورة، مما قد يقلل حجمها أكثر. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | الدقة المستهدفة للضغط، محددة كقيمة من تعداد [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/). |

### قيمة الإرجاع

قيمة من نوع **bool** تشير إلى ما إذا تم ضغط الصورة بنجاح. تُرجع ****true****

## ملاحظات

تقوم هذه الطريقة بتغيير حجم الصورة ودقتها مشابهًا لميزة "Picture Format -> Compress Pictures" في PowerPoint.

إذا تم تعديل حجم الصورة أو قصها، وإلا ****false****

.

يوضح المثال التالي كيفية استخدام طريقة **CompressImage** لتقليل حجم صورة في عرض تقديمي عن طريق ضبط الدقة المستهدفة وإزالة المناطق المقصوصة:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// ضغط الصورة بدقة مستهدفة 150 DPI (دقة الويب) وإزالة المناطق المقصوصة
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) طريقة

يقوم بضغط الصورة عن طريق تقليل حجمها بناءً على حجم الشكل والدقة المحددة. اختياريًا، يحذف أيضًا المناطق المقصوصة.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | إذا كان true، ستزيل الطريقة المناطق المقصوصة من الصورة، مما قد يقلل حجمها أكثر. |
| resolution | **float** | الدقة المستهدفة بوحدة DPI. يجب أن تكون هذه القيمة موجبة وتحدد كيفية تغيير حجم الصورة. |

### قيمة الإرجاع

قيمة من نوع **bool** تشير إلى ما إذا تم ضغط الصورة بنجاح. تُرجع ****true****

## ملاحظات

تقوم هذه الطريقة بتغيير حجم الصورة ودقتها مشابهًا لميزة "Picture Format -> Compress Pictures" في PowerPoint.

إذا تم تعديل حجم الصورة أو قصها، وإلا ****false****

.

يوضح المثال التالي كيفية استخدام طريقة **CompressImage** لتقليل حجم صورة في عرض تقديمي عن طريق ضبط الدقة المستهدفة وإزالة المناطق المقصوصة:
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// يحصل على إطار الصورة
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// ضغط الصورة بدقة مستهدفة 150 DPI (دقة الويب) وإزالة المناطق المقصوصة
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // دقة الويب
```

## انظر أيضًا

* تعداد [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* فئة [IPictureFillFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)