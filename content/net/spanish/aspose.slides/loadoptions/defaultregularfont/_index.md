---
title: DefaultRegularFont
second_title: Aspose.Sildes para .NET Referencia de API
description: Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String.
type: docs
weight: 40
url: /es/aspose.slides/loadoptions/defaultregularfont/
---

## Propiedad LoadOptions.DefaultRegularFont

Devuelve o establece la fuente Regular utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String.

```csharp
public string DefaultRegularFont { get; set; }
```

### Ejemplos

El siguiente ejemplo muestra cómo establecer fuentes predeterminadas para el renderizado de presentaciones de PowerPoint.

```csharp
[C#]
// Utilizar opciones de carga para definir las fuentes regulares y asiáticas predeterminadas
LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
loadOptions.DefaultRegularFont = "Wingdings";
loadOptions.DefaultAsianFont = "Wingdings";
// Cargar la presentación
using (Presentation pptx = new Presentation("DefaultFonts.pptx", loadOptions))
{
    // Generar miniatura de la diapositiva
    pptx.Slides[0].GetThumbnail(1, 1).Save("output_out.png", ImageFormat.Png);
    // Generar PDF
    pptx.Save("output_out.pdf", SaveFormat.Pdf);
    // Generar XPS
    pptx.Save("output_out.xps", SaveFormat.Xps);
}
```

### Véase También

* class [LoadOptions](../../loadoptions)
* namespace [Aspose.Slides](../../loadoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->