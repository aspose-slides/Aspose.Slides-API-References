---
title: get_Description()
second_title: Aspose.Slides for C++ API संदर्भ
description: Summary Zoom Section ऑब्जेक्ट का पाठ विवरण लौटाता है।
type: docs
weight: 27
url: /hi/aspose.slides/isummaryzoomsection/get_description/
---
## ISummaryZoomSection::get_Description() विधि

Summary Zoom [Section](../../section/) ऑब्जेक्ट का पाठ विवरण लौटाता है।

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Description()=0
```

## टिप्पणी

उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## देखें

* क्लास [String](../../../system/string/)
* क्लास [ISummaryZoomSection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)