---
title: IsPasswordProtected
second_title: Aspose.Sildes para Referencia de API .NET
description: Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. Solo lectura Boolean.
type: docs
weight: 20
url: /es/aspose.slides.vba/vbaproject/ispasswordprotected/
---

## Propiedad VbaProject.IsPasswordProtected

Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. Solo lectura Boolean.

```csharp
public bool IsPasswordProtected { get; }
```

### Ejemplos

```csharp
[C#]
using (var presentation = new Presentation(path + "demo.pptm"))
{
    if (presentation.VbaProject.IsPasswordProtected)
        Console.WriteLine("El VBAProject '" + presentation.VbaProject.Name + 
            "' está protegido por contraseña para ver las propiedades del proyecto.");
}
```

### Ver También

* clase [VbaProject](../../vbaproject)
* espacio de nombres [Aspose.Slides.Vba](../../vbaproject)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->