---
title: set_ImageType()
second_title: Aspose.Slides برای مرجع API C++
description: "نوع تصویر یک شی زوم را تنظیم می‌کند. ZoomImageType را بنویسید. مقدار پیش‌فرض: Preview"
type: docs
weight: 14
url: /fa/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) متد

نوع تصویر یک شی زوم را تنظیم می‌کند. [ZoomImageType](../../zoomimagetype/) را بنویسید. مقدار پیش‌فرض: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## توضیحات

مشخص می‌کند که آیا شی Zoom از پیش‌نمایش اسلاید استفاده می‌کند یا تصویر پوششی.

این مثال تغییر نوع تصویر به مقدار Preview را نشان می‌دهد. در این حالت تصویر فعلی یک شی Zoom به تصویر اسلاید تغییر می‌کند:

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## موارد مرتبط

* enum [ZoomImageType](../../zoomimagetype/)
* کلاس [IZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)