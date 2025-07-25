---
title: IsWriteProtected
second_title: Aspose.Sildes para .NET Referencia de API
description: Obtiene un valor que indica si una presentación vinculada está protegida contra escritura.
type: docs
weight: 30
url: /es/aspose.slides/presentationinfo/iswriteprotected/
---

## PresentationInfo.IsWriteProtected propiedad

Obtiene un valor que indica si una presentación vinculada está protegida contra escritura.

```csharp
public NullableBool IsWriteProtected { get; }
```

### Observaciones

Si la presentación está protegida por una contraseña para abrir, el valor de la propiedad es NotDefined.

### Ejemplos

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
if (info.IsWriteProtected == NullableBool.True)
{
    Console.WriteLine("La presentación '" + presentationFilePath + "' está protegida contra escritura por una contraseña.");
}
```

### Véase también

* enum [NullableBool](../../nullablebool)
* class [PresentationInfo](../../presentationinfo)
* namespace [Aspose.Slides](../../presentationinfo)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->