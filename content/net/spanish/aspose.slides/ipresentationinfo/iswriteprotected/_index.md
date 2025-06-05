---
title: IsWriteProtected
second_title: Aspose.Slides para .NET Referencia de API
description: Obtiene un valor que indica si una presentación vinculada está protegida contra escritura.
type: docs
weight: 30
url: /es/aspose.slides/ipresentationinfo/iswriteprotected/
---

## IPresentationInfo.IsWriteProtected propiedad

Obtiene un valor que indica si una presentación vinculada está protegida contra escritura.

```csharp
public NullableBool IsWriteProtected { get; }
```

### Notas

Si la presentación está protegida por una contraseña para abrir, el valor de la propiedad es igual a NotDefined. Consulte la enumeración [`NullableBool`](../../nullablebool).

### Ejemplos

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
if (info.IsWriteProtected == NullableBool.True)
{
    Console.WriteLine("La presentación '" + presentationFilePath + "' está protegida contra escritura por una contraseña.");
}
```

### Véase También

* enum [NullableBool](../../nullablebool)
* interface [IPresentationInfo](../../ipresentationinfo)
* namespace [Aspose.Slides](../../ipresentationinfo)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->