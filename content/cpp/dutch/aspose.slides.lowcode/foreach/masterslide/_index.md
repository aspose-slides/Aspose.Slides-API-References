---
title: MasterSlide()
second_title: Aspose.Slides voor C++ API-referentie
description: "Itereer elk ForEach::MasterSlide in de Presentatie."
type: docs
weight: 14
url: /nl/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) methode


Itereer elk [ForEach::MasterSlide](./) in de [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) om master slides te itereren |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | Callback die voor elke master slide wordt aangeroepen |
## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [ForEach](../)
* Naamruimte [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)