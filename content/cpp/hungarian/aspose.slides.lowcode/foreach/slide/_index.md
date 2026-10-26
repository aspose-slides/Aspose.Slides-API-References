---
title: Slide()
second_title: Aspose.Slides for C++ API hivatkozás
description: "Iterálja a ForEach::Slide-ot a Presentation-ben."
type: docs
weight: 1
url: /hu/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) metódus

Iterálja a(z) [ForEach::Slide](./)-t a [Presentation](../../../aspose.slides/presentation/)-ben.

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) diákok iterálásához |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback, amely minden diára meghívásra kerül |

## Megjegyzések

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [ForEachSlideCallback](../foreachslidecallback/)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Osztály [ForEach](../)
* Névtér [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)