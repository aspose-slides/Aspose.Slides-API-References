---
title: Collect
second_title: Aspose.Slides für C++ API Referenz
description: Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, Modellobjekte unterschiedlicher Typen aus Presentation zu sammeln.
type: docs
weight: 1
url: /de/aspose.slides.lowcode/collect/
---
## Collect Klasse

Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, Modellobjekte unterschiedlicher Typen aus [Presentation](../../aspose.slides/presentation/) zu sammeln.

```cpp
class Collect
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Sammelt alle Instanzen von [Shape](../../aspose.slides/shape/) im [Presentation](../../aspose.slides/presentation/). |

## Anmerkungen

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... ändern Sie die Formformatierung oder andere Eigenschaften
}
```

## Siehe auch

* Namensraum [Aspose::Slides::LowCode](../)
* Bibliothek [Aspose.Slides](../../)