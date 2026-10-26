---
title: LayoutSlide()
second_title: Riferimento API Aspose.Slides per C++
description: "Itera ogni ForEach::LayoutSlide nella Presentazione."
type: docs
weight: 27
url: /it/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachLayoutSlideCallback) metodo


Itera ogni [ForEach::LayoutSlide](./) nel [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) per iterare le diapositive di layout |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | Callback che verrà invocato per ogni diapositiva di layout |
## Osservazioni




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [ForEach](../)
* Spazio dei nomi [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)