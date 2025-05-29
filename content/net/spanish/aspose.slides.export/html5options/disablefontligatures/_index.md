---
title: DisableFontLigatures
second_title: Referencia de API de Aspose.Sildes para .NET
description: Obtiene o establece un valor que indica si el texto se renderiza sin utilizar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en false.
type: docs
weight: 40
url: /es/aspose.slides.export/html5options/disablefontligatures/
---

## Propiedad Html5Options.DisableFontLigatures

Obtiene o establece un valor que indica si el texto se renderiza sin utilizar ligaduras. Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en `false`.

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
        DisableFontLigatures = true // Desactivar ligaduras en la renderización del texto
    };
    
    pres.Save(outputSlidePath, SaveFormat.Html5, options);
}
```

### Ver también

* clase [Html5Options](../../html5options)
* espacio de nombres [Aspose.Slides.Export](../../html5options)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->