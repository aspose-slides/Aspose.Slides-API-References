---
title: get_TargetSection()
second_title: مرجع API Aspose.Slides للـ C++
description: يحصل على كائن القسم الذي يرتبط به كائن Section Zoom. اقرأ ISection.
type: docs
weight: 1
url: /ar/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() طريقة


يحصل على كائن القسم الذي يرتبط به كائن [Section](../../section/) Zoom. اقرأ [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## ملاحظات


هذا المثال يوضح تغيير القسم المستهدف وإنشاء صورة جديدة لكائن تكبير القسم:
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
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)