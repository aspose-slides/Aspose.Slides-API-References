---
title: Collect
second_title: Aspose.Slides pro C++ API Reference
description: Představuje skupinu metod určených ke sběru objektů modelu různých typů z Presentation.
type: docs
weight: 1
url: /cs/aspose.slides.lowcode/collect/
---
## Collect třída

Představuje skupinu metod určených ke sběru objektů modelu různých typů z [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Sbírá všechny instance [Shape](../../aspose.slides/shape/) v [Presentation](../../aspose.slides/presentation/). |

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... změnit formátování tvaru nebo jiné vlastnosti
}
```

## Viz také

* Jmenný prostor [Aspose::Slides::LowCode](../)
* Knihovna [Aspose.Slides](../../)