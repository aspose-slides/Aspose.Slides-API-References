---
title: set_ShowBackground()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. اكتب bool. القيمة الافتراضية: true"
type: docs
weight: 66
url: /ar/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) طريقة

يضبط القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. اكتب **bool**. القيمة الافتراضية: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## ملاحظات

يوضح المثال إزالة خلفية صورة لكائن Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## انظر أيضًا

* فئة [ZoomObject](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)