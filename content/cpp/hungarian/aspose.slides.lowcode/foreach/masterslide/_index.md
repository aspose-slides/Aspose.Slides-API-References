---
title: MasterSlide()
second_title: Aspose.Slides a C++ API hivatkozása
description: "Iterálja a prezentációban lévő minden ForEach::MasterSlide elemet."
type: docs
weight: 14
url: /hu/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) metódus

Iteráljon minden [ForEach::MasterSlide](./) a [Presentation](../../../aspose.slides/presentation/)-ban.

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) a master diákok iterálásához |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | Visszahívás, amely minden master slide esetén meghívásra kerül |

## Megjegyzések

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Osztály [ForEach](../)
* Névtér [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)