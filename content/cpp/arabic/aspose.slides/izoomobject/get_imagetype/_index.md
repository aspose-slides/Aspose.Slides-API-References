---
title: get_ImageType()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يقوم بالحصول على نوع الصورة لكائن Zoom. اقرأ ZoomImageType. القيمة الافتراضية: Preview"
type: docs
weight: 1
url: /ar/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() طريقة

يسترجع نوع الصورة لكائن Zoom. اقرأ [ZoomImageType](../../zoomimagetype/). القيمة الافتراضية: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## ملاحظات

يحدد ما إذا كان كائن Zoom يستخدم معاينة الشريحة أو صورة غلاف.

يوضح هذا المثال تغيير Image Type إلى القيمة Preview. في هذه الحالة تتغير الصورة الحالية لكائن Zoom إلى صورة الشريحة:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## انظر أيضاً

* تعداد [ZoomImageType](../../zoomimagetype/)
* فئة [IZoomObject](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)