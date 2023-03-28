---
title: LayoutSlide()
second_title: Aspose.Slides for C++ API Reference
description: "Iterate each ForEach::LayoutSlide in the Presentation."
type: docs
weight: 27
url: /cpp/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide([System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)) method


Iterate each [ForEach::LayoutSlide](./) in the [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) to iterate layout slides |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | Callback that will be invoked for each layout slide |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Typedef [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
