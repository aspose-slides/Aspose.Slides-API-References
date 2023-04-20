---
title: get_Title()
second_title: Aspose.Slides for C++ API Reference
description: Returns the text title of the Summary Zoom Section object.
type: docs
weight: 1
url: /cpp/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() method


Returns the text title of the Summary Zoom [Section](../../section/) object.

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
```

## Remarks


Example: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## See Also

* Class [String](../../../system/string/)
* Class [SummaryZoomSection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)