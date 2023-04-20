---
title: get_TargetSection()
second_title: Aspose.Slides for C++ API Reference
description: Gets the section object that the Section Zoom object is linked to. Read ISection.
type: docs
weight: 1
url: /cpp/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() method


Gets the section object that the [Section](../../section/) Zoom object is linked to. Read [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
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