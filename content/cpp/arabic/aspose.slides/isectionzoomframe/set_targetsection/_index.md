---
title: set_TargetSection()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط كائن القسم الذي يرتبط به كائن Section Zoom. اكتب ISection.
type: docs
weight: 14
url: /ar/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) طريقة

يضبط كائن القسم الذي يرتبط به كائن [Section](../../section/) Zoom. اكتب [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## ملاحظات

يوضح هذا المثال تغيير القسم الهدف وينشئ صورة جديدة لكائن تكبير القسم: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISection](../../isection/)
* فئة [ISectionZoomFrame](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)