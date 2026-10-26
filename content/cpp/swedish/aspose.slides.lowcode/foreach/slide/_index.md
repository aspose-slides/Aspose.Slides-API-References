---
title: Slide()
second_title: Aspose.Slides för C++ API-referens
description: "Iterera varje ForEach::Slide i Presentationen."
type: docs
weight: 1
url: /sv/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) metod


Iterera varje [ForEach::Slide](./) i [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) för att iterera bilder |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback som kommer att anropas för varje bild |
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```




## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Typdefinition [ForEachSlideCallback](../foreachslidecallback/)
* Klass [Presentation](../../../aspose.slides/presentation/)
* Klass [ForEach](../)
* Namnrymd [Aspose::Slides::LowCode](../../)
* Bibliotek [Aspose.Slides](../../../)