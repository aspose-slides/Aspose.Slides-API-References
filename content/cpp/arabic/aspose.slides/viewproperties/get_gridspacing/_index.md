---
title: get_GridSpacing()
second_title: Aspose.Slides لمرجع API للـ C++
description: يعيد مسافة الشبكة التي يجب استخدامها للشبكة الأساسية لمستند العرض التقديمي، بالنقاط. قراءة float.
type: docs
weight: 92
url: /ar/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() طريقة

يعيد مسافة الشبكة التي يجب استخدامها للشبكة الأساسية لمستند العرض التقديمي، بالنقاط. قراءة **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## ملاحظات

يجب أن تكون قيمة مسافة الشبكة رقمًا موجبًا. النطاق النموذجي للقيمة هو من 1 مم (2.8349607 نقاط) إلى 2 بوصة (144 نقطة).

الشيفرة النموذجية التالية توضح كيفية تغيير مسافة الشبكة في عرض PowerPoint.

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* فئة [ViewProperties](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)