---
title: SaveMetafilesAsPng
second_title: Aspose.Sildes para .NET Referencia de API
description: Verdadero para convertir todos los metafiles utilizados en una presentación a imágenes PNG. Lectura/escritura Boolean.
type: docs
weight: 160
url: /es/aspose.slides.export/pdfoptions/savemetafilesaspng/
---

## Propiedad PdfOptions.SaveMetafilesAsPng

Verdadero para convertir todos los metafiles utilizados en una presentación a imágenes PNG. Lectura/escritura Boolean.

```csharp
public bool SaveMetafilesAsPng { get; set; }
```

### Observaciones

El valor por defecto es **true**. Un documento Pdf puede contener gráficos vectoriales e imágenes rasterizadas. Si SaveMetafilesAsPng se establece en true, entonces la imagen Metafile fuente se convierte al formato Png y se guarda en Pdf como una imagen rasterizada. Si SaveMetafilesAsPng se establece en false, entonces el Metafile fuente se convierte a gráficos vectoriales Pdf. Cada enfoque tiene ventajas y desventajas. Por ejemplo, si el Metafile se convierte a PNG, entonces es posible que haya alguna pérdida de calidad durante la escalación del documento resultante. Si el Metafile se convierte a gráficos vectoriales Pdf, entonces es posible que haya problemas de rendimiento en la herramienta de visualización de Pdf.

### Ver También

* clase [PdfOptions](../../pdfoptions)
* espacio de nombres [Aspose.Slides.Export](../../pdfoptions)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->