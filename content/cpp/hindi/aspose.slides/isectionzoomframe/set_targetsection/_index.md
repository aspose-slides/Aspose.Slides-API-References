---
title: set_TargetSection()
second_title: Aspose.Slides for C++ API संदर्भ
description: सेक्शन ज़ूम ऑब्जेक्ट से जुड़ा सेक्शन ऑब्जेक्ट सेट करता है। लिखें ISection.
type: docs
weight: 14
url: /hi/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) विधि

ऐसे सेक्शन ऑब्जेक्ट को सेट करता है जिससे [Section](../../section/) Zoom ऑब्जेक्ट जुड़ा होता है। लिखें [ISection](../../isection/)।

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* वर्ग [ISection](../../isection/)
* वर्ग [ISectionZoomFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)