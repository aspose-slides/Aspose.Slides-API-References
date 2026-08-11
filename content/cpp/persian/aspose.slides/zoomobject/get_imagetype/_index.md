---
title: get_ImageType()
second_title: مرجع API Aspose.Slides برای C++
description: "نوع تصویر یک شی Zoom را دریافت می‌کند. ببینید ZoomImageType. مقدار پیش‌فرض: Preview"
type: docs
weight: 1
url: /fa/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() method

نوع تصویر یک شی Zoom را دریافت می‌کند. ببینید [ZoomImageType](../../zoomimagetype/). مقدار پیش‌فرض: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## Remarks

مشخص می‌کند که آیا شی Zoom از پیش‌نمایش اسلاید یا تصویر پوشش استفاده می‌کند.

مثال بعدی نشان می‌دهد که چگونه Image Type را به مقدار Preview تغییر داد. در این حالت تصویر فعلی یک شی Zoom به تصویر اسلاید تغییر می‌کند:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## See Also

* شمارشی [ZoomImageType](../../zoomimagetype/)
* کلاس [ZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)