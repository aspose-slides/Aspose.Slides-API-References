---
title: get_Sections()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति में परिभाषित सभी स्लाइड सेक्शन की सूची लौटाता है। केवल-पढ़ने योग्य ISectionCollection.
type: docs
weight: 66
url: /hi/aspose.slides/presentation/get_sections/
---
## Presentation::get_Sections() विधि

प्रस्तुति में परिभाषित सभी स्लाइड सेक्शन की सूची लौटाता है। केवल-पढ़ने योग्य [ISectionCollection](../../isectioncollection/).

```cpp
System::SharedPtr<ISectionCollection> Aspose::Slides::Presentation::get_Sections() override
```

## टिप्पणियाँ

निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint [Presentation](../) में सेक्शन कैसे बनाते हैं।
```cpp
auto pres = System::MakeObject<Presentation>();

auto defaultSlide = pres->get_Slides()->idx_get(0);
auto layoutSlide = pres->get_LayoutSlides()->idx_get(0);
auto newSlide1 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide2 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide3 = pres->get_Slides()->AddEmptySlide(layoutSlide);
auto newSlide4 = pres->get_Slides()->AddEmptySlide(layoutSlide);

System::SharedPtr<ISection> section1 = pres->get_Sections()->AddSection(u"Section 1", newSlide1);
// section1 को newSlide2 पर समाप्त किया जाएगा और उसके बाद section2 शुरू होगा
System::SharedPtr<ISection> section2 = pres->get_Sections()->AddSection(u"Section 2", newSlide3);

pres->Save(u"pres-sections.pptx", SaveFormat::Pptx);
pres->get_Sections()->ReorderSectionWithSlides(section2, 0);
pres->Save(u"pres-sections-moved.pptx", SaveFormat::Pptx);
pres->get_Sections()->RemoveSectionWithSlides(section2);
pres->get_Sections()->AppendEmptySection(u"Last empty section");
pres->Save(u"pres-section-with-empty.pptx", SaveFormat::Pptx);
```
 निम्नलिखित उदाहरण दिखाते हैं कि सेक्शन के नाम कैसे बदलें।
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<ISection> section = pres->get_Sections()->idx_get(0);
section->set_Name(u"My section");
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISectionCollection](../../isectioncollection/)
* क्लास [Presentation](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)