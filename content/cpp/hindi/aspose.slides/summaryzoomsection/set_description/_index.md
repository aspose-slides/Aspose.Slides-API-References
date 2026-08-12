---
title: set_Description()
second_title: Aspose.Slides for C++ API संदर्भ
description: Summary Zoom Section ऑब्जेक्ट का टेक्स्ट विवरण लौटाता है।
type: docs
weight: 40
url: /hi/aspose.slides/summaryzoomsection/set_description/
---
## SummaryZoomSection::set_Description(System::String) विधि


Summary Zoom [Section](../../section/) ऑब्जेक्ट का टेक्स्ट विवरण लौटाता है।

```cpp
void Aspose::Slides::SummaryZoomSection::set_Description(System::String value) override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [SummaryZoomSection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)