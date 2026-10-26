---
title: get_ZoomImage()
second_title: Aspose.Slides برای مرجع API C++
description: تصویر برای شی Zoom دریافت می‌کند. ببینید IPPImage.
type: docs
weight: 79
url: /fa/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() متد

دریافت تصویر برای شی Zoom. ببینید [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## توضیحات

این مثال نشان می‌دهد که چگونه تصویر یک شی Zoom را تغییر دهید:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IPPImage](../../ippimage/)
* کلاس [ZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)