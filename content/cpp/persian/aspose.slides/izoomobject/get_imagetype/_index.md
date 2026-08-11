---
title: get_ImageType()
second_title: مرجع API Aspose.Slides برای C++
description: "نوع تصویر یک شیء Zoom را دریافت می‌کند. ZoomImageType را بخوانید. مقدار پیش‌فرض: Preview"
type: docs
weight: 1
url: /fa/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() متد

نوع تصویر یک شیء Zoom را دریافت می‌کند. مطالعه کنید [ZoomImageType](../../zoomimagetype/). مقدار پیش‌فرض: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## توضیحات

مشخص می‌کند که آیا شیء Zoom از پیش‌نمایش اسلاید یا تصویر کاور استفاده می‌کند.

این مثال نشان می‌دهد که تغییر Image Type به مقدار Preview. در این حالت تصویر فعلی یک شیء Zoom به تصویر اسلاید تغییر می‌کند:

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## مراجع

* Enum [ZoomImageType](../../zoomimagetype/)
* کلاس [IZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)