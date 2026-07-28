---
title: MasterSlide()
second_title: Odwołanie API Aspose.Slides dla C++
description: "Iteruj każdy ForEach::MasterSlide w Presentation."
type: docs
weight: 14
url: /pl/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) metoda


Iteruj każdy [ForEach::MasterSlide](./) w [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) do iteracji master slides |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | Wywołanie zwrotne, które zostanie wywołane dla każdego master slide |
## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## Zobacz również

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* Klasa [Presentation](../../../aspose.slides/presentation/)
* Klasa [ForEach](../)
* Przestrzeń nazw [Aspose::Slides::LowCode](../../)
* Biblioteka [Aspose.Slides](../../../)