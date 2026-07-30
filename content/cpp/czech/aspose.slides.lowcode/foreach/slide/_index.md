---
title: Slide()
second_title: Reference API Aspose.Slides pro C++
description: "Iterujte každý ForEach::Slide v prezentaci."
type: docs
weight: 1
url: /cs/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) metoda

Iterujte každý [ForEach::Slide](./) v [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) to iterate slides |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback that will be invoked for each slide |
## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* Třída [Presentation](../../../aspose.slides/presentation/)
* Třída [ForEach](../)
* Jmenný prostor [Aspose::Slides::LowCode](../../)
* Knihovna [Aspose.Slides](../../../)