---
title: set_GridSpacing()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط تباعد الشبكة الذي يجب استخدامه للشبكة التي تدعم مستند العرض التقديمي، بوحدات النقاط. اكتب float.
type: docs
weight: 105
url: /ar/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) طريقة

يضبط تباعد الشبكة الذي يجب استخدامه للشبكة التي تدعم مستند العرض التقديمي، بوحدات النقاط. اكتب **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## ملاحظات

يجب أن تكون قيمة تباعد الشبكة رقمًا موجبًا. النطاق القيمي المعتاد هو من 1 مم (2.8349607 نقطة) إلى 2 بوصة (144 نقطة).

يعرض الكود العيني التالي كيفية تغيير تباعد الشبكة في عرض تقديمي لبرنامج PowerPoint.

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [IViewProperties](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)