---
title: Slide()
second_title: Riferimento API di Aspose.Slides per C++
description: "Itera ogni ForEach::Slide nella Presentazione."
type: docs
weight: 1
url: /it/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) method

Itera ogni [ForEach::Slide](./) nel [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) per iterare le diapositive |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback che verrà invocata per ogni diapositiva |

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Libreria [Aspose.Slides](../../../)