---
title: get_ImageType()
second_title: Aspose.Slides لمرجع API C++
description: "يحصل على نوع الصورة لكائن التكبير. اقرأ ZoomImageType. القيمة الافتراضية: Preview"
type: docs
weight: 1
url: /ar/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() طريقة

يحصل على نوع الصورة لكائن التكبير. اقرأ [ZoomImageType](../../zoomimagetype/). القيمة الافتراضية: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## ملاحظات

يحدد ما إذا كان كائن Zoom يستخدم معاينة الشريحة أو صورة الغلاف.

المثال التالي يوضح تغيير Image Type إلى القيمة Preview. في هذه الحالة تتغير الصورة الحالية لكائن Zoom إلى صورة الشريحة:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## انظر أيضًا

* تعداد [ZoomImageType](../../zoomimagetype/)
* فئة [ZoomObject](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)