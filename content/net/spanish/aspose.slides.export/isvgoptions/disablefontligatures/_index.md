---
title: DisableFontLigatures
second_title: Aspose.Sildes para .NET API Reference
description: Obtiene o establece un valor que indica si el texto se renderiza sin el uso de ligaduras. Cuando se establece en verdadero, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en falso.
type: docs
weight: 40
url: /es/aspose.slides.export/isvgoptions/disablefontligatures/
---

## ISVGOptions.DisableFontLigatures property

Obtiene o establece un valor que indica si el texto se renderiza sin el uso de ligaduras. Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en `false`.

```csharp
public bool DisableFontLigatures { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    SVGOptions options = new SVFOptions
    {
        DisableFontLigatures = true // Desactivar ligaduras en el renderizado de texto
    };
    
    using (FileStream fileStream = new FileStream("slide-0.svg", FileMode.Create, FileAccess.Write))
    {
        pres.Slides[0].WriteAsSvg(fileStream);   
    }
}
```

### Ver También

* interface [ISVGOptions](../../isvgoptions)
* namespace [Aspose.Slides.Export](../../isvgoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->