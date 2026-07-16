---
title: Collect
second_title: Référence API Aspose.Slides pour C++
description: Représente un groupe de méthodes destinées à collecter des objets modèle de différents types depuis Presentation.
type: docs
weight: 1
url: /fr/aspose.slides.lowcode/collect/
---
## Collect classe

Représente un groupe de méthodes destinées à collecter des objets modèle de différents types depuis [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Méthodes

| Méthode | Description |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Collecte toutes les instances de [Shape](../../aspose.slides/shape/) dans le [Presentation](../../aspose.slides/presentation/). |
## Remarques



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... modifier le format de la forme ou d'autres propriétés
}
```

## Voir aussi

* Espace de noms [Aspose::Slides::LowCode](../)
* Bibliothèque [Aspose.Slides](../../)