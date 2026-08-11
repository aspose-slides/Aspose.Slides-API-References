---
title: get_TargetSection()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يجلب كائن القسم الذي يرتبط به كائن Section Zoom. اقرأ ISection.
type: docs
weight: 1
url: /ar/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() طريقة

يجلب كائن القسم الذي يرتبط به كائن [Section](../../section/) Zoom. اقرأ [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## ملاحظات

المثال التالي يوضح تغيير القسم المستهدف وإنشاء صورة جديدة لكائن تكبير القسم:

```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISection](../../isection/)
* فئة [SectionZoomFrame](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)