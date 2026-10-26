---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides برای C++ مرجع API
description: حذف نواحی برش‌خوردهٔ پرکنندهٔ تصویر.
type: docs
weight: 430
url: /fa/aspose.slides/picturefillformat/deletepicturecroppedareas/
---
## PictureFillFormat::DeletePictureCroppedAreas() متد

ناحیه‌های بریده‌شدهٔ پرکننده را حذف کنید [Picture](../../picture/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::PictureFillFormat::DeletePictureCroppedAreas() override
```

### مقدار بازگشت

تصویر برش‌خورده یا تصویر اصلی اگر برش لازم نباشد.

## ملاحظات

این متد فایل‌های متا‌فایل WMF/EMF را به تصویر PNG پیکسلی تبدیل می‌کند و در حین برش انجام می‌دهد.

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Gets the PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// Deletes cropped areas of the PictureFrame image
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)