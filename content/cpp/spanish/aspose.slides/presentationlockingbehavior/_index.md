---
title: PresentationLockingBehavior
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa el comportamiento respecto al tratamiento de la fuente IPresentation (archivo o System::IO::Stream) al cargar y trabajar con una instancia de IPresentation."
type: docs
weight: 6748
url: /es/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enumeración

Representa el comportamiento respecto al tratamiento de la fuente [IPresentation](../ipresentation/) (archivo o [System::IO::Stream](../../system.io/stream/)) al cargar y trabajar con una instancia de [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| LoadAndRelease | 0 | La fuente se bloqueará solo durante la ejecución del constructor [IPresentation](../ipresentation/). |
| KeepLocked | 1 | La fuente se bloqueará durante todo el tiempo de vida de la instancia [IPresentation](../ipresentation/), hasta que se libere. |

## Observaciones

La fuente es el parámetro pasado al constructor [IPresentation](../ipresentation/). En el ejemplo a continuación, la fuente es el archivo "pres.pptx":

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

Para este ejemplo, la fuente (archivo "pres.pptx") permanecerá bloqueada durante la vida de la instancia [IPresentation](../ipresentation/), es decir, no podrá ser modificada ni eliminada por otro proceso.

## Ver también

* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)