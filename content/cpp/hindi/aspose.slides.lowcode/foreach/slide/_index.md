---
title: Slide()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Presentation में प्रत्येक ForEach::Slide को इटरिट करें।"
type: docs
weight: 1
url: /hi/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) मेथड


प्रत्येक [ForEach::Slide](./) को [Presentation](../../../aspose.slides/presentation/) में इटरिट करें।

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) स्लाइड्स पर इटरिट करने के लिए |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback that will be invoked for each slide |
## टिप्पणी




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```




## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* क्लास [Presentation](../../../aspose.slides/presentation/)
* क्लास [ForEach](../)
* नेमस्पेस [Aspose::Slides::LowCode](../../)
* लाइब्रेरी [Aspose.Slides](../../../)