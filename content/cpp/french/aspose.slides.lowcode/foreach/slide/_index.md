---
title: Slide()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Parcourir chaque ForEach::Slide dans la Présentation."
type: docs
weight: 1
url: /fr/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) méthode

Parcourir chaque [ForEach::Slide](./) dans le [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) pour parcourir les diapositives |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Fonction de rappel qui sera invoquée pour chaque diapositive |

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)