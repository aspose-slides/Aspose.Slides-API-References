---
title: get_SlideSize()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य ISlideSize।
type: docs
weight: 79
url: /hi/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() विधि

स्लाइड आकार ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [ISlideSize](../../islidesize/)।

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## टिप्पणी

निम्न उदाहरण दर्शाता है कि PowerPoint [Presentation](../) में स्लाइड आकार कैसे बदलें।
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
निम्न उदाहरण दर्शाता है कि PowerPoint [Presentation](../) के लिए कंटेंट स्केलिंग के साथ स्लाइड आकार कैसे सेट करें।
```cpp
// एक Presentation ऑब्जेक्ट बनाएं जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// निर्मित प्रस्तुतियों का स्लाइड आकार स्रोत के समान सेट करें
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// SetSize मेथड का उपयोग स्केल कंटेंट के साथ स्लाइड आकार सेट करने के लिए किया जाता है ताकि फिट हो सके
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// SetSize मेथड का उपयोग कंटेंट के आकार को अधिकतम करने के साथ स्लाइड आकार सेट करने के लिए किया जाता है
// प्रस्तुति को डिस्क पर सहेजें
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
निम्न उदाहरण दर्शाता है कि PowerPoint [Presentation](../) में कस्टम स्लाइड आकार कैसे निर्दिष्ट करें।
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// A4 कागज आकार
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlideSize](../../islidesize/)
* क्लास [Presentation](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)