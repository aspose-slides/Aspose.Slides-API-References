---
title: set_Title()
second_title: Aspose.Slides C++ API संदर्भ
description: Summary Zoom Section वस्तु का पाठ शीर्षक लौटाता है।
type: docs
weight: 14
url: /hi/aspose.slides/isummaryzoomsection/set_title/
---
## ISummaryZoomSection::set_Title(System::String) विधि


Summary Zoom [Section](../../section/) वस्तु का पाठ शीर्षक लौटाता है।

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Title(System::String value)=0
```

## टिप्पणी


उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## देखें भी

* वर्ग [String](../../../system/string/)
* वर्ग [ISummaryZoomSection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)