---
title: Slide()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Iteruj każdy ForEach::Slide w prezentacji."
type: docs
weight: 1
url: /pl/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) metoda


Iteruj każdy [ForEach::Slide](./) w [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) do iteracji slajdów |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Wywołanie zwrotne, które zostanie wywołane dla każdego slajdu |
## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```




## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* Klasa [Presentation](../../../aspose.slides/presentation/)
* Klasa [ForEach](../)
* Przestrzeń nazw [Aspose::Slides::LowCode](../../)
* Biblioteka [Aspose.Slides](../../../)