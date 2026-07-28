---
title: Collect
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Reprezentuje grupę metod przeznaczonych do zbierania obiektów modelu różnych typów z Presentation.
type: docs
weight: 1
url: /pl/aspose.slides.lowcode/collect/
---
## Collect klasa

Reprezentuje grupę metod przeznaczonych do zbierania obiektów modelu różnych typów z [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Zbiera wszystkie wystąpienia [Shape](../../aspose.slides/shape/) w [Presentation](../../aspose.slides/presentation/). |
## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... zmień formatowanie kształtu lub inne właściwości
}
```

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::LowCode](../)
* Biblioteka [Aspose.Slides](../../)