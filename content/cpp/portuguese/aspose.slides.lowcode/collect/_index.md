---
title: Collect
second_title: Aspose.Slides para C++ Referência da API
description: Representa um grupo de métodos destinado a coletar objetos de modelo de diferentes tipos de Presentation.
type: docs
weight: 1
url: /pt/aspose.slides.lowcode/collect/
---
## Collect classe

Representa um grupo de métodos destinado a coletar objetos de modelo de diferentes tipos de [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Coleta todas as instâncias de [Shape](../../aspose.slides/shape/) no [Presentation](../../aspose.slides/presentation/). |
## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... altere a formatação da forma ou outras propriedades
}
```

## Veja também

* Espaço de nomes [Aspose::Slides::LowCode](../)
* Biblioteca [Aspose.Slides](../../)