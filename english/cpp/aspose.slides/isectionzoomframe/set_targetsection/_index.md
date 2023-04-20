---
title: set_TargetSection()
second_title: Aspose.Slides for C++ API Reference
description: Sets the section object that the Section Zoom object is linked to. Write ISection.
type: docs
weight: 14
url: /cpp/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) method


Sets the section object that the [Section](../../section/) Zoom object is linked to. Write [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Remarks


This example demonstrates changing target section and creates a new image for the section zoom object: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [ISectionZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)