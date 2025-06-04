---
title: DisableFontLigatures
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en verdadero, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en falso.
type: docs
weight: 40
url: /es/aspose.slides.export/html5options/disablefontligatures/
---

## Html5Options.DisableFontLigatures property

Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en `false`.

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
        DisableFontLigatures = true // Desactivar ligaduras en la renderización de texto
    };
    
    pres.Save(outputSlidePath, SaveFormat.Html5, options);
}
```

### Véase también

* class [Html5Options](../../html5options)
* namespace [Aspose.Slides.Export](../../html5options)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->