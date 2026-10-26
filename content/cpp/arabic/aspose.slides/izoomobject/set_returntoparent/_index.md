---
title: set_ReturnToParent()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يضبط سلوك التنقل في عرض الشرائح. اكتب bool. القيمة الافتراضية: false"
type: docs
weight: 40
url: /ar/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) طريقة


يضبط سلوك التنقل في عرض الشرائح. اكتب **bool**. القيمة الافتراضية: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## ملاحظات


القيمة True للخاصية تحدد سلوك العودة إلى العنصر الأصلي في عرض الشرائح. 

مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## انظر أيضًا

* فئة [IZoomObject](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)