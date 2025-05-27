---
title: DefaultTextLanguage
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve o establece el idioma predeterminado para el texto de la presentación. Cadena de lectura/escritura.
type: docs
weight: 50
url: /es/aspose.slides/iloadoptions/defaulttextlanguage/
---

## Propiedad ILoadOptions.DefaultTextLanguage

Devuelve o establece el idioma predeterminado para el texto de la presentación. Cadena de lectura/escritura.

```csharp
public string DefaultTextLanguage { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
// Utiliza las opciones de carga para definir la cultura de texto predeterminada
LoadOptions loadOptions = new LoadOptions();
loadOptions.DefaultTextLanguage = "en-US";
using (Presentation pres = new Presentation(loadOptions))
 {
    // Agregar nueva forma de rectángulo con texto
    IAutoShape shp = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
    shp.TextFrame.Text = "New Text";

    // Verificar el idioma de la primera porción
    Console.WriteLine(shp.TextFrame.Paragraphs[0].Portions[0].PortionFormat.LanguageId);
}
```

### Vea También

* interfaz [ILoadOptions](../../iloadoptions)
* espacio de nombres [Aspose.Slides](../../iloadoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->