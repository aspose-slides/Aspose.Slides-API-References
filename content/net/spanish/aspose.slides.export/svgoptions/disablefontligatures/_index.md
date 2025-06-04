---
title: DisableFontLigatures
second_title: Aspose.Slides para .NET API Reference
description: Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está configurada en false.
type: docs
weight: 70
url: /es/aspose.slides.export/svgoptions/disablefontligatures/
---

## SVGOptions.DisableFontLigatures propiedad

Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está configurada en `false`.

```csharp
public bool DisableFontLigatures { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    SVGOptions options = new SVGOptions
    {
        DisableFontLigatures = true // Desactivar ligaduras en la renderización del texto
    };
    
    using (FileStream fileStream = new FileStream("slide-0.svg", FileMode.Create, FileAccess.Write))
    {
        pres.Slides[0].WriteAsSvg(fileStream);   
    }
}
```

### Véase También

* class [SVGOptions](../../svgoptions)
* namespace [Aspose.Slides.Export](../../svgoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->