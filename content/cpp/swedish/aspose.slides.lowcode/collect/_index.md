---
title: Collect
second_title: Aspose.Slides för C++ API-referens
description: Representerar en grupp metoder avsedda att samla modellobjekt av olika typer från Presentation.
type: docs
weight: 1
url: /sv/aspose.slides.lowcode/collect/
---
## Collect klass


Representerar en grupp metoder avsedda att samla modellobjekt av olika typer från [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Samlar alla instanser av [Shape](../../aspose.slides/shape/) i [Presentation](../../aspose.slides/presentation/). |
## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... ändra shape-formattering eller andra egenskaper
}
```

## Se även

* Namnrymd [Aspose::Slides::LowCode](../)
* Bibliotek [Aspose.Slides](../../)