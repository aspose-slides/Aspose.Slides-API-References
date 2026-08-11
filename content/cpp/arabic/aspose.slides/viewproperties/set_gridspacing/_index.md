---
title: set_GridSpacing()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد تباعد الشبكة الذي يجب استخدامه للشبكة الأساسية في مستند العرض التقديمي، بالنقاط. اكتب float.
type: docs
weight: 105
url: /ar/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) طريقة


يحدد تباعد الشبكة الذي يجب استخدامه للشبكة الأساسية في مستند العرض التقديمي، بالنقاط. اكتب **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## ملاحظات


يجب أن تكون قيمة تباعد الشبكة عدداً موجباً. النطاق النموذجي للقيمة هو من 1 مم (2.8349607 نقطة) إلى 2 بوصة (144 نقطة).

يوضح الكود العيني التالي كيفية تعديل تباعد الشبكة في عرض تقديمي من PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* الفئة [ViewProperties](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)