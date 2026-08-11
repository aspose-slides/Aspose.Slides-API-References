---
title: get_ReturnToParent()
second_title: "مرجع API لـ Aspose.Slides للغة C++"
description: "يحصل على سلوك التنقل في عرض الشرائح. قراءة bool. القيمة الافتراضية: false"
type: docs
weight: 27
url: /ar/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() طريقة

يحصل على سلوك التنقل في عرض الشرائح. قراءة **bool**. القيمة الافتراضية: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## ملاحظات

القيمة true للخاصية تحدد سلوك العودة إلى العنصر الأصلي في عرض الشرائح.

مثال:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## انظر أيضًا

* الفئة [ZoomObject](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)