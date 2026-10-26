---
title: set_ReturnToParent()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: "يضبط سلوك التنقل في عرض الشرائح. اكتب bool. القيمة الافتراضية: false"
type: docs
weight: 40
url: /ar/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) طريقة


يضبط سلوك التنقل في عرض الشرائح. اكتب **bool**. القيمة الافتراضية: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## ملاحظات


القيمة true للخاصية تحدد سلوك العودة إلى الأصل في عرض الشرائح. 

مثال:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## انظر أيضاً

* صنف [ZoomObject](../)
* فضاء الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)