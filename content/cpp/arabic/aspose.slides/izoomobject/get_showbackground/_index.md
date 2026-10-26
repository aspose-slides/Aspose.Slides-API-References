---
title: get_ShowBackground()
second_title: مرجع API Aspose.Slides للغة C++
description: "يحصل على القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. قراءة bool. القيمة الافتراضية: true"
type: docs
weight: 53
url: /ar/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() طريقة

يحصل على القيمة التي تحدد ما إذا كان Zoom سيستخدم خلفية الشريحة الوجهة. قراءة **bool**. القيمة الافتراضية: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
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

* الفئة [IZoomObject](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)