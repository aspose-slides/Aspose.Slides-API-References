---
title: set_TargetSection()
second_title: Aspose.Slides for C++ API Reference
description: Sets the section object that the Section Zoom object links to. Write ISection.
type: docs
weight: 14
url: /cpp/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection([System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\>) method


Sets the section object that the [Section](../../section/) Zoom object links to. Write [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## Remarks


Next example demonstrates changing target section and creates new image for the section zoom object: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISection](../../isection/)
* Class [SectionZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
