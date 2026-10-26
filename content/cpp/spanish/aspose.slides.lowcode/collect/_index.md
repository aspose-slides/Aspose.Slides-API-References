---
title: Collect
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un grupo de métodos destinados a recopilar objetos de modelo de diferentes tipos de Presentation.
type: docs
weight: 1
url: /es/aspose.slides.lowcode/collect/
---
## Collect clase


Representa un grupo de métodos destinados a recopilar objetos de modelo de diferentes tipos de [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Recopila todas las instancias de [Shape](../../aspose.slides/shape/) en el [Presentation](../../aspose.slides/presentation/). |
## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... cambiar el formato de la forma o otras propiedades
}
```

## Ver también

* Espacio de nombres [Aspose::Slides::LowCode](../)
* Biblioteca [Aspose.Slides](../../)