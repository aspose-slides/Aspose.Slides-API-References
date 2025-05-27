---
title: RefreshThumbnail
second_title: Referencia de API de Aspose.Sildes para .NET
description: Especifica si la miniatura de la presentación se actualizará. Booleano de lectura/escritura. El valor predeterminado es verdadero.
type: docs
weight: 30
url: /es/aspose.slides.export/ipptxoptions/refreshthumbnail/
---

## Propiedad IPptxOptions.RefreshThumbnail

Especifica si la miniatura de la presentación se actualizará. Booleano de lectura/escritura. El valor predeterminado es **true**.

```csharp
public bool RefreshThumbnail { get; set; }
```

### Observaciones

Cuando el valor de la opción es **true**, se generará la nueva miniatura.

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

### Véase También

* interfaz [IPptxOptions](../../ipptxoptions)
* espacio de nombres [Aspose.Slides.Export](../../ipptxoptions)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->