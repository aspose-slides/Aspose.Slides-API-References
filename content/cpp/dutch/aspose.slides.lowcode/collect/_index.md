---
title: Collect
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een groep methoden voor die bedoeld zijn om modelobjecten van verschillende typen uit Presentation te verzamelen.
type: docs
weight: 1
url: /nl/aspose.slides.lowcode/collect/
---
## Collect klasse

Stelt een groep methoden voor die bedoeld zijn om modelobjecten van verschillende typen te verzamelen uit [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Verzamelt alle instanties van [Shape](../../aspose.slides/shape/) in de [Presentation](../../aspose.slides/presentation/). |
## Opmerkingen


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... wijzig shape-opmaak of andere eigenschappen
}
```

## Zie ook

* Naamruimte [Aspose::Slides::LowCode](../)
* Bibliotheek [Aspose.Slides](../../)