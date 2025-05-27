---
title: Persistencia
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene el método utilizado para almacenar propiedades del control ActiveX. Solo lectura PersistenceTypeaspose.slides/persistencetype.
type: docs
weight: 50
url: /es/aspose.slides/control/persistence/
---

## Propiedad Control.Persistence

Obtiene el método utilizado para almacenar propiedades del control ActiveX. Solo lectura [`PersistenceType`](../../persistencetype).

```csharp
public PersistenceType Persistence { get; }
```

### Ejemplos

El siguiente ejemplo muestra el uso de la propiedad Persistence para verificar si las propiedades del objeto ActiveX pueden ser cambiadas como propiedades ActiveX basadas en XML:

```csharp
[C#]
if (control.Persistence == PersistenceType.PersistPropertyBag)
{
    control.Properties["Value"] = value;
}
else
{
    YourMethodHere(control.ActiveXControlBinary); //Usa tu propio método para gestionar propiedades de ActiveX almacenadas en su archivo binario
}
```

### Ver También

* enum [PersistenceType](../../persistencetype)
* class [Control](../../control)
* namespace [Aspose.Slides](../../control)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->