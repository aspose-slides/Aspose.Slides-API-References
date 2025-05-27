---
title: IsPasswordProtected
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene un valor que indica si una presentación vinculada está protegida por una contraseña para abrir.
type: docs
weight: 20
url: /es/aspose.slides/ipresentationinfo/ispasswordprotected/
---

## IPresentationInfo.IsPasswordProtected propiedad

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

### Véase también

* interface [IPresentationInfo](../../ipresentationinfo)
* namespace [Aspose.Slides](../../ipresentationinfo)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->