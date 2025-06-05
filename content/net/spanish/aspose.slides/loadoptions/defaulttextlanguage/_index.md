---
title: DefaultTextLanguage
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve o establece el idioma predeterminado para el texto de la presentación. Cadena de lectura/escritura.
type: docs
weight: 60
url: /es/aspose.slides/loadoptions/defaulttextlanguage/
---

## Propiedad LoadOptions.DefaultTextLanguage

Devuelve o establece el idioma predeterminado para el texto de la presentación. Cadena de lectura/escritura.

```csharp
public string DefaultTextLanguage { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
// Utiliza opciones de carga para definir la cultura de texto predeterminada
LoadOptions loadOptions = new LoadOptions();
loadOptions.DefaultTextLanguage = "en-US";
using (Presentation pres = new Presentation(loadOptions))
 {
    // Agrega una nueva forma rectangular con texto
    IAutoShape shp = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
    shp.TextFrame.Text = "Nuevo Texto";

    // Verifica el idioma de la primera porción
    Console.WriteLine(shp.TextFrame.Paragraphs[0].Portions[0].PortionFormat.LanguageId);
}
```

### Ver También

* class [LoadOptions](../../loadoptions)
* namespace [Aspose.Slides](../../loadoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->