---
title: DeletePictureCroppedAreas()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: حذف المناطق المقصوصة من تعبئة الصورة.
type: docs
weight: 430
url: /ar/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() طريقة


حذف المناطق المقصوصة من التعبئة [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```


### قيمة الإرجاع

صورة مقصوصة أو الصورة الأصلية إذا لم يكن الاقتصاص ضروريًا.

## ملاحظات


هذه الطريقة تحول ملفات WMF/EMF الوصفية إلى صورة PNG نقطية أثناء القص.



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// الحصول على PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// حذف المناطق المقصوصة من صورة PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IPPImage](../../ippimage/)
* فئة [PictureFillFormat](../)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)