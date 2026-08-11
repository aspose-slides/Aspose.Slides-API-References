---
title: get_ZoomImage()
second_title: Aspose.Slides برای C++ مرجع API
description: تصویر برای شیء زوم دریافت می‌کند. IPPImage را بخوانید.
type: docs
weight: 79
url: /fa/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() متد


تصویر برای شیء زوم دریافت می‌کند. بخوانید [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## توضیحات


این مثال تغییر تصویر یک شیء زوم را نشان می‌دهد:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IPPImage](../../ippimage/)
* کلاس [IZoomObject](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)