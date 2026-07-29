---
title: MasterSlide()
second_title: Aspose.Slides för C++ API-referens
description: "Iterera varje ForEach::MasterSlide i Presentationen."
type: docs
weight: 14
url: /sv/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) metod


Iterera varje [ForEach::MasterSlide](./) i [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) för att iterera master-bilder |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | Callback som kommer att anropas för varje master-bild |
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* Klass [Presentation](../../../aspose.slides/presentation/)
* Klass [ForEach](../)
* Namnrymd [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)