---
title: set_TargetSection()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: सेक्शन ज़ूम ऑब्जेक्ट द्वारा लिंक किए जाने वाले सेक्शन ऑब्जेक्ट को सेट करता है। ISection लिखें।
type: docs
weight: 14
url: /hi/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) विधि

सेक्शन ऑब्जेक्ट को सेट करता है जिससे [Section](../../section/) Zoom ऑब्जेक्ट लिंक करता है। [ISection](../../isection/) लिखें।

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## टिप्पणियाँ

अगला उदाहरण लक्ष्य सेक्शन बदलने और सेक्शन ज़ूम ऑब्जेक्ट के लिए नई छवि बनाने को दर्शाता है:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ISection](../../isection/)
* क्लास [SectionZoomFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)