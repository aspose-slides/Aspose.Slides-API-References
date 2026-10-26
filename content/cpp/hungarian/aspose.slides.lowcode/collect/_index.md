---
title: Collect
second_title: Aspose.Slides C++ API referenciája
description: Egy csoport metódust képvisel, amely a Presentation-ből származó különböző típusú modellobjektumok összegyűjtésére szolgál.
type: docs
weight: 1
url: /hu/aspose.slides.lowcode/collect/
---
## Collect osztály


Egy csoport metódust képvisel, amely a különböző típusú modellobjektumok összegyűjtésére szolgál a [Presentation](../../aspose.slides/presentation/)-ból.

```cpp
class Collect
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Az összes [Shape](../../aspose.slides/shape/) példányt a [Presentation](../../aspose.slides/presentation/)-ban gyűjti össze. |
## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... alakzat formázásának vagy egyéb tulajdonságok módosítása
}
```

## Lásd még

* Névtér [Aspose::Slides::LowCode](../)
* Könyvtár [Aspose.Slides](../../)