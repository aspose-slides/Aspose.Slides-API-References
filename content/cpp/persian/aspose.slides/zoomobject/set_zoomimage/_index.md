---
title: set_ZoomImage()
second_title: Aspose.Slides برای C++ مرجع API
description: تصویر را برای شی Zoom تنظیم می‌کند. IPPImage را بنویسید.
type: docs
weight: 92
url: /fa/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) متد


تصویر را برای شی Zoom تنظیم می‌کند. [IPPImage](../../ippimage/) را بنویسید.

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## توضیحات


این مثال تغییر تصویر یک شی Zoom را نشان می‌دهد:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IPPImage](../../ippimage/)
* کلاس [ZoomObject](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)