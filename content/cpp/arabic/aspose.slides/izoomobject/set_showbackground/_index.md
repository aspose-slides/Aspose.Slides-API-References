---
title: set_ShowBackground()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. اكتب bool. القيمة الافتراضية: true"
type: docs
weight: 66
url: /ar/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) طريقة

يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. اكتب **bool**. القيمة الافتراضية: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## ملاحظات

يوضح المثال كيفية إزالة خلفية صورة كائن Zoom:

```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## انظر أيضًا

* فئة [IZoomObject](../)
* نطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)