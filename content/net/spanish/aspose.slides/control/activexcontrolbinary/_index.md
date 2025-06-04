---
title: ActiveXControlBinary
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica la persistencia de un control ActiveX cuando el método utilizado para persistir es ya sea PersistStream, PersistStreamInit o PersistStorage.
type: docs
weight: 10
url: /es/aspose.slides/control/activexcontrolbinary/
---

## Propiedad Control.ActiveXControlBinary

Especifica la persistencia de un control ActiveX cuando el método utilizado para persistir es ya sea PersistStream, PersistStreamInit o PersistStorage.

```csharp
public byte[] ActiveXControlBinary { get; }
```

### Ejemplos

El siguiente ejemplo muestra el uso de la propiedad ActiveXControlBinary para cambiar las propiedades de ActiveX:

```csharp
[C#]
if (control.Persistence == PersistenceType.PersistPropertyBag)
{
    control.Properties["Value"] = value;
}
else
{
    YourMethodHere(control.ActiveXControlBinary); //Utilice su propio método para gestionar las propiedades de ActiveX almacenadas en su archivo binario
}
```

### Ver También

* clase [Control](../../control)
* espacio de nombres [Aspose.Slides](../../control)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->