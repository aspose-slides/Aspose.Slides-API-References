---
title: Collect
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un gruppo di metodi destinati a raccogliere oggetti modello di diversi tipi da Presentation.
type: docs
weight: 1
url: /it/aspose.slides.lowcode/collect/
---
## Classe Collect

Rappresenta un gruppo di metodi destinati a raccogliere oggetti modello di tipi diversi da [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Raccoglie tutte le istanze di [Shape](../../aspose.slides/shape/) nel [Presentation](../../aspose.slides/presentation/). |
## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... modifica la formattazione della forma o altre proprietà
}
```

## Vedi anche

* Spazio dei nomi [Aspose::Slides::LowCode](../)
* Libreria [Aspose.Slides](../../)