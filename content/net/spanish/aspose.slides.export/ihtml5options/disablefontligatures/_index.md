---
title: DisableFontLigatures
second_title: Aspose.Sildes para referencia de la API .NET
description: Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en verdadero, las ligaduras se desactivarán en la salida renderizada. De forma predeterminada, esta propiedad está establecida en falso.
type: docs
weight: 40
url: /es/aspose.slides.export/ihtml5options/disablefontligatures/
---

## Propiedad IHtml5Options.DisableFontLigatures

Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. De forma predeterminada, esta propiedad está establecida en `false`.

```csharp
public bool DisableFontLigatures { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Html5Options options = new Html5Options
    {
        DisableFontLigatures = true // Desactivar ligaduras en el renderizado de texto
    };
    
    pres.Save(outputSlidePath, SaveFormat.Html5, options);
}
```

### Ver También

* interfaz [IHtml5Options](../../ihtml5options)
* espacio de nombres [Aspose.Slides.Export](../../ihtml5options)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
