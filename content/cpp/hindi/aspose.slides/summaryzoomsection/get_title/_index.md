---
title: get_Title()
second_title: Aspose.Slides for C++ API संदर्भ
description: Summary Zoom Section ऑब्जेक्ट का टेक्स्ट शीर्षक लौटाता है।
type: docs
weight: 1
url: /hi/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() मेथड

Summary Zoom [Section](../../section/) ऑब्जेक्ट का टेक्स्ट शीर्षक लौटाता है।

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## देखें

* क्लास [String](../../../system/string/)
* क्लास [SummaryZoomSection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)