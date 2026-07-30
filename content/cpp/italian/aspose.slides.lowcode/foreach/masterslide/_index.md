---
title: MasterSlide()
second_title: Riferimento API di Aspose.Slides per C++
description: "Itera ciascuno ForEach::MasterSlide nella Presentation."
type: docs
weight: 14
url: /it/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) metodo

Itera ogni [ForEach::MasterSlide](./) nel [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) per iterare le diapositive master |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | Callback che verrà invocata per ogni diapositiva master |

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [ForEach](../)
* Spazio dei nomi [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)