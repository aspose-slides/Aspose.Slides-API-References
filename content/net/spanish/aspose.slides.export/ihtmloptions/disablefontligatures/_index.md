---
title: DisableFontLigatures
second_title: Referencia de la API de Aspose.Sildes para .NET
description: Obtiene o establece un valor que indica si el texto se representa sin utilizar ligaduras. Cuando se establece en true, las ligaduras se deshabilitarán en la salida renderizada. Por defecto, esta propiedad está configurada como false.
type: docs
weight: 30
url: /es/aspose.slides.export/ihtmloptions/disablefontligatures/
---

## IHtmlOptions.DisableFontLigatures propiedad

Obtiene o establece un valor que indica si el texto se representa sin utilizar ligaduras. Cuando se establece en `true`, las ligaduras se deshabilitarán en la salida renderizada. Por defecto, esta propiedad está configurada como `false`.

```csharp
public bool DisableFontLigatures { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    HtmlOptions options = new HtmlOptions
    {
        DisableFontLigatures = true // Desactivar ligaduras en el renderizado del texto
    };
    
    pres.Save(outputSlidePath, SaveFormat.Html, options);
}
```

### Ver También

* interfaz [IHtmlOptions](../../ihtmloptions)
* espacio de nombres [Aspose.Slides.Export](../../ihtmloptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->