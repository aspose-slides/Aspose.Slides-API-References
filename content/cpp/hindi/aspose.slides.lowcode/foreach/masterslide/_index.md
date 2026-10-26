---
title: MasterSlide()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "Presentation में प्रत्येक ForEach::MasterSlide को दोहराएँ।"
type: docs
weight: 14
url: /hi/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) विधि

प्रत्येक [ForEach::MasterSlide](./) को [Presentation](../../../aspose.slides/presentation/) में दोहराएँ।

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) master slides को दोहराने के लिए |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | Callback जो प्रत्येक master slide के लिए बुलाया जाएगा |
## टिप्पणी

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* वर्ग [Presentation](../../../aspose.slides/presentation/)
* वर्ग [ForEach](../)
* नामस्थान [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)