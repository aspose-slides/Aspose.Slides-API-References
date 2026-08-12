---
title: LayoutSlide()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Presentation में प्रत्येक ForEach::LayoutSlide को इटररेट करें।"
type: docs
weight: 27
url: /hi/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachLayoutSlideCallback) मेथड


प्रत्येक [ForEach::LayoutSlide](./) को [Presentation](../../../aspose.slides/presentation/) में इटररेट करें।

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) लेआउट स्लाइड्स को इटररेट करने के लिए |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | प्रत्येक लेआउट स्लाइड के लिए कॉल किया जाएगा |
## टिप्पणी




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडेफ़ [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* क्लास [Presentation](../../../aspose.slides/presentation/)
* क्लास [ForEach](../)
* नेमस्पेस [Aspose::Slides::LowCode](../../)
* लाइब्रेरी [Aspose.Slides](../../../)