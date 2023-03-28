---
title: Portion()
second_title: Aspose.Slides for C++ API Reference
description: "Iterate each ForEach::Portion in the Presentation."
type: docs
weight: 66
url: /cpp/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion([System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](../foreachportioncallback/)) method


Iterate each [ForEach::Portion](./) in the [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) to iterate portions |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback that will be invoked for each portion |
## Remarks


Portions will be iterated in all type of slides - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) and [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
