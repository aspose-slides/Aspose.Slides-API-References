---
title: get_ReturnToParent()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ C++
description: "يحصل على سلوك التنقل في عرض الشرائح. قراءة bool. القيمة الافتراضية: false"
type: docs
weight: 27
url: /ar/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() طريقة

يحصل على سلوك التنقل في عرض الشرائح. قراءة **bool**. القيمة الافتراضية: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## ملاحظات

القيمة True للخاصية تحدد سلوك العودة إلى الأصل في عرض الشرائح.

مثال:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## انظر أيضًا

* الفئة [IZoomObject](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)