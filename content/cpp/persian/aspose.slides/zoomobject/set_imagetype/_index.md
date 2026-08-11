---
title: set_ImageType()
second_title: Aspose.Slides برای C++ مستندات API
description: "نوع تصویر یک شیء زوم را تنظیم می‌کند. مقدار ZoomImageType را بنویسید. مقدار پیش‌فرض: Preview"
type: docs
weight: 14
url: /fa/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) متد


نوع تصویر یک شیء زوم را تنظیم می‌کند. نوشتن [ZoomImageType](../../zoomimagetype/). مقدار پیش‌فرض: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## توضیحات


مشخص می‌کند که آیا شیء Zoom از پیش‌نمایش اسلاید یا یک تصویر کاور استفاده می‌کند. 

نمونه بعدی تغییر Image Type به مقدار Preview را نشان می‌دهد. در این مورد تصویر فعلی یک Zoom object به تصویر اسلاید تغییر می‌کند: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## موارد مرتبط

* شمارش [ZoomImageType](../../zoomimagetype/)
* کلاس [ZoomObject](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)