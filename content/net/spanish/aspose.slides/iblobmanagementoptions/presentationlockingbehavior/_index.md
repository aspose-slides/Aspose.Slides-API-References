---
title: Comportamiento deBloqueoDePresentacion
second_title: Referencia de la API Aspose.Sildes para .NET
description: Esta propiedad define si una instancia de la clase Presentation puede ser propietaria de la fuente - archivo o flujo durante la vida útil de la instancia. Si la instancia es propietaria, bloquea la fuente. Esto ayuda a mejorar el consumo de memoria y el rendimiento al trabajar con BLOBs, pero el flujo o archivo fuente no puede ser cambiado durante la vida útil de la instancia de Presentación. Este es un ejemplo
type: docs
weight: 30
url: /es/aspose.slides/iblobmanagementoptions/presentationlockingbehavior/
---

## Propiedad IBlobManagementOptions.PresentationLockingBehavior

Esta propiedad define si una instancia de la clase Presentation puede ser propietaria de la fuente - archivo o flujo durante la vida útil de la instancia. Si la instancia es propietaria, bloquea la fuente. Esto ayuda a mejorar el consumo de memoria y el rendimiento al trabajar con BLOBs, pero la fuente (flujo o archivo) no puede ser cambiada durante la vida útil de la instancia de Presentación. Este es un ejemplo:

```csharp
public PresentationLockingBehavior PresentationLockingBehavior { get; set; }
```

### Ejemplos

```csharp
LoadOptions loadOptions = new LoadOptions { 
  BlobManagementOptions = {PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked} };
using (Presentation pres = new Presentation("pres.pptx", loadOptions)) {
  // Se lanzará IOException porque pres.pptx está bloqueado para la vida útil de la Presentación
  // File.Delete("pres.pptx");
}
// después de que el objeto Presentation se elimine, el archivo se desbloquea y se puede eliminar
File.Delete("pres.pptx");
```

### También Visto

* enum [PresentationLockingBehavior](../../presentationlockingbehavior)
* interface [IBlobManagementOptions](../../iblobmanagementoptions)
* namespace [Aspose.Slides](../../iblobmanagementoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->