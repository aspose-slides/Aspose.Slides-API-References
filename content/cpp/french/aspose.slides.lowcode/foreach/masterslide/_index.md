---
title: MasterSlide()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Parcourir chaque ForEach::MasterSlide dans la Presentation."
type: docs
weight: 14
url: /fr/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) méthode

Parcourir chaque [ForEach::MasterSlide](./) dans le [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) pour parcourir les diapositives maîtres |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | Rappel qui sera invoqué pour chaque diapositive maître |

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [ForEach](../)
* Espace de noms [Aspose::Slides::LowCode](../../)
* Bibliothèque [Aspose.Slides](../../../)