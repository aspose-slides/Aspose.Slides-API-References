---
title: set_ImageType()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يضبط نوع الصورة لكائن التكبير. اكتب ZoomImageType. القيمة الافتراضية: Preview"
type: docs
weight: 14
url: /ar/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) طريقة

يضبط نوع الصورة لكائن التكبير. اكتب [ZoomImageType](../../zoomimagetype/). القيمة الافتراضية: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## ملاحظات

يحدد ما إذا كان كائن Zoom يستخدم معاينة الشريحة أو صورة غلاف.

توضح المثال التالي تغيير Image Type إلى القيمة Preview. في هذه الحالة تتغير الصورة الحالية لكائن Zoom إلى صورة الشريحة:

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## انظر أيضًا

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)