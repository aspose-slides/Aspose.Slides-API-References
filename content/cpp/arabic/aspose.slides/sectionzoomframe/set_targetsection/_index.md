---
title: set_TargetSection()
second_title: Aspose.Slides لمرجع API C++
description: يضبط كائن القسم الذي يرتبط به كائن Section Zoom. كتابة ISection.
type: docs
weight: 14
url: /ar/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) طريقة

يقوم بتعيين كائن القسم الذي يرتبط به كائن [Section](../../section/) Zoom. كتابة [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## ملاحظات

المثال التالي يوضح تغيير القسم المستهدف وإنشاء صورة جديدة لكائن تكبير القسم:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [SectionZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)