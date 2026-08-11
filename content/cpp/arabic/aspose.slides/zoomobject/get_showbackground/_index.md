---
title: get_ShowBackground()
second_title: Aspose.Slides لمرجع API C++
description: "يحصل على القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. قراءة bool. القيمة الافتراضية: true"
type: docs
weight: 53
url: /ar/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() طريقة

يحصل على القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الهدف. قراءة **bool**. القيمة الافتراضية: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## ملاحظات

يوضح المثال إزالة خلفية صورة كائن Zoom:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## انظر أيضًا

* الفئة [ZoomObject](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)