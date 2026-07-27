---
title: get_PresentationLockingBehavior()
second_title: Referencia de API de Aspose.Slides para C++
description: "Esta propiedad define si una instancia de la clase Presentation puede ser propietaria de la fuente - archivo o flujo durante la vida de la instancia. Si la instancia es propietaria, bloquea la fuente. Esto ayuda a mejorar el consumo de memoria y el rendimiento al trabajar con BLOBs, pero la fuente (flujo o archivo) no puede cambiarse durante la vida de la instancia de Presentation. Este es un ejemplo:"
type: docs
weight: 1
url: /es/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() método


Esta propiedad define si una instancia de la clase [Presentation](../../presentation/) puede ser propietaria de la fuente - archivo o flujo durante la vida de la instancia. Si la instancia es propietaria, bloquea la fuente. Esto ayuda a mejorar el consumo de memoria y el rendimiento al trabajar con BLOBs, pero la fuente (flujo o archivo) no puede cambiarse durante la vida de la instancia de [Presentation](../../presentation/). Este es un ejemplo:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Observaciones



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // Se lanzará IOException porque pres.pptx está bloqueado durante la vida de la Presentation
    // File::Delete(u"pres.pptx");
}
// después de que el objeto Presentation sea destruido, el archivo se desbloquea y puede ser eliminado
IO::File::Delete(u"pres.pptx");
```

## Ver también

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Clase [IBlobManagementOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)