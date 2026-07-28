---
title: LayoutSlide()
second_title: Aspose.Slides C++ API referencia
description: "Iterálja a Presentation minden ForEach::LayoutSlide elemét."
type: docs
weight: 27
url: /hu/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachLayoutSlideCallback) metódus

Iterálja minden [ForEach::LayoutSlide](./)-t a [Presentation](../../../aspose.slides/presentation/)-ben.

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) a elrendezési diák iterálásához |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | Visszahívás, amely minden elrendezési diánál meghívásra kerül |

## Megjegyzések

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)