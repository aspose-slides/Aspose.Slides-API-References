---
title: Slide()
second_title: Aspose.Slides für C++ API-Referenz
description: "Iteriere jedes ForEach::Slide in der Presentation."
type: docs
weight: 1
url: /de/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) Methode

Iteriere jedes [ForEach::Slide](./) in der [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) zum Durchlaufen von Folien |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback, der für jede Folie aufgerufen wird |

## Bemerkungen

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [ForEach](../)
* Namensraum [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)