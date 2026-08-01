---
title: Slide()
second_title: Aspose.Slides voor C++ API-referentie
description: "Itereer elke ForEach::Slide in de Presentatie."
type: docs
weight: 1
url: /nl/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) methode

Itereer elk [ForEach::Slide](./) in de [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) om dia's te itereren |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback die wordt aangeroepen voor elke dia |

## Opmerkingen

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [ForEach](../)
* Naamruimte [Aspose::Slides::LowCode](../../)
* Bibliotheek [Aspose.Slides](../../../)