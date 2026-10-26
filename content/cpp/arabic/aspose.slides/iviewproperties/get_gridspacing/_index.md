---
title: get_GridSpacing()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد الفاصل الشبكي الذي يجب استخدامه للشبكة التي تدعم مستند العرض التقديمي، بوحدة النقاط. قراءة float.
type: docs
weight: 92
url: /ar/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() طريقة


يعيد الفاصل الشبكي الذي يجب استخدامه للشبكة التي تدعم مستند العرض التقديمي، بوحدة النقاط. قراءة **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## ملاحظات


يجب أن تكون قيمة الفاصل الشبكي رقمًا موجبًا. النطاق النموذجي للقيمة هو من 1 مم (2.8349607 نقاط) إلى 2 إنش (144 نقطة). 

يظهر الكود النموذجي التالي كيفية تغيير الفاصل الشبكي في عرض تقديمي من PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [IViewProperties](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)