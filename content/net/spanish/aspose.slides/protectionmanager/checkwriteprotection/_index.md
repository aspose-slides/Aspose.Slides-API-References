---
title: CheckWriteProtection
second_title: Referencia de API de Aspose.Slides para .NET
description: Determina si una presentación está protegida por contraseña para modificar.
type: docs
weight: 70
url: /es/aspose.slides/protectionmanager/checkwriteprotection/
---

## ProtecciónManager.CheckWriteProtection método

Determina si una presentación está protegida por contraseña para modificar.

```csharp
public bool CheckWriteProtection(string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | String | La contraseña para verificar. |

### Valor de retorno

True si la contraseña es válida; de lo contrario, false.

### Comentarios

1. Debe verificar la propiedad [`IsWriteProtected`](../iswriteprotected) antes de llamar a este método. 2. Cuando la contraseña es nula o está vacía, este método devuelve false.

### Ejemplos

```csharp
[C#]
using (var presentation = new Presentation(presentationFilePath))
{
    var isWriteProtected = presentation.ProtectionManager.CheckWriteProtection("my_password");
}
```

### Ver también

* clase [ProtectionManager](../../protectionmanager)
* espacio de nombres [Aspose.Slides](../../protectionmanager)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
