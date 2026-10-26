---
title: DeletePictureCroppedAreas()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: احذف المناطق المقصوصة من تعبئة Picture.
type: docs
weight: 430
url: /ar/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() طريقة

احذف المناطق المقصوصة من التعبئة [Picture](../../picture/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```

### قيمة الإرجاع

الصورة المقطوعة أو الصورة الأصلية إذا لم يكن القص ضروريًا.

## ملاحظات

تحول هذه الطريقة ملفات WMF/EMF الوصفية إلى صورة PNG نقطية أثناء القص.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Deletes cropped areas of the PictureFrame image
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IPPImage](../../ippimage/)
* فئة [IPictureFillFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)