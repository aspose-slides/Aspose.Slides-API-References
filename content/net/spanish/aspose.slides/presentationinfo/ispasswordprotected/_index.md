---
title: IsPasswordProtected
second_title: Referencia de la API de Aspose.Sildes para .NET
description: Obtiene un valor que indica si una presentación vinculada está protegida por una contraseña para abrir.
type: docs
weight: 20
url: /es/aspose.slides/presentationinfo/ispasswordprotected/
---

## Propiedad PresentationInfo.IsPasswordProtected

Obtiene un valor que indica si una presentación vinculada está protegida por una contraseña para abrir.

```csharp
public bool IsPasswordProtected { get; }
```

### Ejemplos

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
if (info.IsPasswordProtected)
{
    Console.WriteLine("La presentación '" + presentationFilePath + "' está protegida por una contraseña para abrir.");
}
```

### Vea También

* clase [PresentationInfo](../../presentationinfo)
* espacio de nombres [Aspose.Slides](../../presentationinfo)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->