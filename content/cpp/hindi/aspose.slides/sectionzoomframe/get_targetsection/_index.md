---
title: get_TargetSection()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: Section Zoom ऑब्जेक्ट द्वारा लिंक किए गए सेक्शन ऑब्जेक्ट को प्राप्त करता है। पढ़ें ISection.
type: docs
weight: 1
url: /hi/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() विधि


उस सेक्शन ऑब्जेक्ट को प्राप्त करता है जिसे [Section](../../section/) Zoom ऑब्जेक्ट लिंक करता है। पढ़ें [ISection](../../isection/)।

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## टिप्पणियाँ


अगला उदाहरण टार्गेट सेक्शन को बदलने और सेक्शन ज़ूम ऑब्जेक्ट के लिए नई छवि बनाने को दर्शाता है: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## और देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISection](../../isection/)
* क्लास [SectionZoomFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)