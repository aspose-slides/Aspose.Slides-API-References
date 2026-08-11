---
title: DeletePictureCroppedAreas()
second_title: Aspose.Slides برای مرجع API C++
description: ناحیه‌های برش‌خوردهٔ پر کردن تصویر را حذف کنید.
type: docs
weight: 430
url: /fa/aspose.slides/ipicturefillformat/deletepicturecroppedareas/
---
## IPictureFillFormat::DeletePictureCroppedAreas() متد


ناحیه‌های برش‌خوردهٔ پر کردن [Picture](../../picture/) را حذف کنید.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IPictureFillFormat::DeletePictureCroppedAreas()=0
```


### مقدار بازگشتی

تصویر برش‌خورده یا تصویر اصلی اگر برش لازم نباشد.

## توضیحات


این متد متا‌فایل‌های WMF/EMF را در حین برش به تصویر PNG رستری تبدیل می‌کند.



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// دریافت PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// حذف نواحی برش‌خورده تصویر PictureFrame
System::SharedPtr<IPPImage> croppedImage = picFrame->get_PictureFormat()->DeletePictureCroppedAreas();
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IPPImage](../../ippimage/)
* کلاس [IPictureFillFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)