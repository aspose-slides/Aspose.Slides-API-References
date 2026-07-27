---
title: Slide()
second_title: Referência da API Aspose.Slides para C++
description: "Itera cada ForEach::Slide na Apresentação."
type: docs
weight: 1
url: /pt/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) método


Iterar cada [ForEach::Slide](./) no [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) para iterar slides |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback que será invocado para cada slide |
## Observações




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```




## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)