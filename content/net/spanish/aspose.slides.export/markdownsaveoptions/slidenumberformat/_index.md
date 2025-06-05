---
title: SlideNumberFormat
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece la cadena de formato utilizada para los encabezados de número de diaposa en la salida de Markdown. El formato debe incluir el marcador de posición 0 que será reemplazado con el índice de la diapositiva durante la exportación. Ejemplo Diapositiva 0 producirá Diapositiva 1, Diapositiva 2, etc.
type: docs
weight: 120
url: /es/aspose.slides.export/markdownsaveoptions/slidenumberformat/
---

## Propiedad MarkdownSaveOptions.SlideNumberFormat

Obtiene o establece la cadena de formato utilizada para los encabezados de número de diapositiva en la salida de Markdown. El formato debe incluir el marcador de posición "{0}", que será reemplazado con el índice de la diapositiva durante la exportación. Ejemplo: "# Diapositiva {0}" producirá "# Diapositiva 1", "# Diapositiva 2", etc.

```csharp
public string SlideNumberFormat { get; set; }
```

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza si el valor proporcionado es nulo o vacío. |
| ArgumentException | Se lanza si la cadena de formato no contiene el marcador de posición "{0}". |

### Véase también

* clase [MarkdownSaveOptions](../../markdownsaveoptions)
* espacio de nombres [Aspose.Slides.Export](../../markdownsaveoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->