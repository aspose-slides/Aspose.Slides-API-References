---
title: MasterSlide()
second_title: Aspose.Slides para Referência da API C++
description: "Itera cada ForEach::MasterSlide na Apresentação."
type: docs
weight: 14
url: /pt/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) método

Itere cada [ForEach::MasterSlide](./) no [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) para iterar slides mestres |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | Callback que será invocado para cada slide mestre |

## Observações

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)