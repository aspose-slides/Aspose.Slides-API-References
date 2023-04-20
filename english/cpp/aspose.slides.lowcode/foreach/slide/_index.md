---
title: Slide()
second_title: Aspose.Slides for C++ API Reference
description: "Iterate each ForEach::Slide in the Presentation."
type: docs
weight: 1
url: /cpp/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) method


Iterate each [ForEach::Slide](./) in the [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) to iterate slides |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback that will be invoked for each slide |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)