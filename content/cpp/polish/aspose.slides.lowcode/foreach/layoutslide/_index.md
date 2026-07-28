---
title: LayoutSlide()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Iteruj każdy ForEach::LayoutSlide w prezentacji."
type: docs
weight: 27
url: /pl/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachLayoutSlideCallback) method

Iteruj każdy [ForEach::LayoutSlide](./) w [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) do iteracji slajdów układu |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | Callback, który zostanie wywołany dla każdego slajdu układu |
## Uwagi

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)