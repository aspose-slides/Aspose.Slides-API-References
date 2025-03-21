---
title: set_Description()
second_title: Aspose.Slides for C++ API Reference
description: Returns the text description of the Summary Zoom Section object.
type: docs
weight: 40
url: /aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) method


Returns the text description of the Summary Zoom [Section](../../section/) object.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
```

## Remarks


Example: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## See Also

* Class [String](../../../system/string/)
* Class [SummaryZoomSection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)