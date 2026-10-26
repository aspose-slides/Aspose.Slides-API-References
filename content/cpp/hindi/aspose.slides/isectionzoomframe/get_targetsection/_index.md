---
title: get_TargetSection()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्राप्त करता है वह सेक्शन ऑब्जेक्ट जिससे Section Zoom ऑब्जेक्ट जुड़ा है। पढ़ें ISection।
type: docs
weight: 1
url: /hi/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() विधि

वह सेक्शन ऑब्जेक्ट प्राप्त करता है जिससे [Section](../../section/) Zoom ऑब्जेक्ट जुड़ा है। पढ़ें [ISection](../../isection/)।

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## टिप्पणियाँ

यह उदाहरण लक्ष्य सेक्शन को बदलने और सेक्शन ज़ूम ऑब्जेक्ट के लिए नई छवि बनाने का प्रदर्शन करता है:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## संबंधित देखें

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISection](../../isection/)
* क्लास [ISectionZoomFrame](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)