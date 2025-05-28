---
title: IsPasswordProtected
second_title: Referencia de API de Aspose.Slides para .NET
description: Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. Solo lectura, Booleano.
type: docs
weight: 10
url: /es/aspose.slides.vba/ivbaproject/ispasswordprotected/
---

## Propiedad IVbaProject.IsPasswordProtected

Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. Solo lectura, Booleano.

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

* interfaz [IVbaProject](../../ivbaproject)
* espacio de nombres [Aspose.Slides.Vba](../../ivbaproject)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->