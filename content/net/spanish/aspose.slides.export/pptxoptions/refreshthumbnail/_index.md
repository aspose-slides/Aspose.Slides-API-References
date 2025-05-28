---
title: RefreshThumbnail
second_title: Referencia de la API Aspose.Slides para .NET
description: Especifica si se actualizará la miniatura de la presentación. Booleano de lectura/escritura. El valor predeterminado es true.
type: docs
weight: 30
url: /es/aspose.slides.export/pptxoptions/refreshthumbnail/
---

## Propiedad PptxOptions.RefreshThumbnail

Especifica si se actualizará la miniatura de la presentación. Booleano de lectura/escritura. El valor predeterminado es **true**.

```csharp
public bool RefreshThumbnail { get; set; }
```

### Observaciones

Cuando el valor de la opción es **true**, se generará una nueva miniatura.

Cuando el valor de la opción es **false**, la miniatura actual se guardará tal como está.

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    pres.Save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, new PptxOptions()
    {
        RefreshThumbnail = false
    });
}
```

### Véase también

* clase [PptxOptions](../../pptxoptions)
* espacio de nombres [Aspose.Slides.Export](../../pptxoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->