---
title: LayoutSlide()
second_title: Aspose.Slides voor C++ API-referentie
description: "Itereer elk ForEach::LayoutSlide in de Presentatie."
type: docs
weight: 27
url: /nl/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachLayoutSlideCallback) methode


Itereer elk [ForEach::LayoutSlide](./) in de [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) om lay-outdia's te itereren |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | Callback die wordt aangeroepen voor elke lay-outdia |
## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [ForEach](../)
* Naamruimte [Aspose::Slides::LowCode](../../)
* Bibliotheek [Aspose.Slides](../../../)