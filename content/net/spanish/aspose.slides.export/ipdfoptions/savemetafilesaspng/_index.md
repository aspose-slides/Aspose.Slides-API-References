---
title: SaveMetafilesAsPng
second_title: Aspose.Slides para .NET Referencia de API
description: Verdadero para convertir todos los metafiles utilizados en una presentación a las imágenes PNG. Lectura/escritura Booleano.
type: docs
weight: 160
url: /es/aspose.slides.export/ipdfoptions/savemetafilesaspng/
---

## IPdfOptions.SaveMetafilesAsPng propiedad

Verdadero para convertir todos los metafiles utilizados en una presentación a las imágenes PNG. Lectura/escritura Booleano.

```csharp
public bool SaveMetafilesAsPng { get; set; }
```

### Observaciones

El valor predeterminado es **true**. El documento Pdf puede contener gráficos vectoriales e imágenes rasterizadas. Si SaveMetafilesAsPng se establece en true, entonces la imagen de Metafile de origen se convierte al formato Png y se guarda en Pdf como una imagen rasterizada. Si SaveMetafilesAsPng se establece en false, entonces el Metafile de origen se convierte a gráficos vectoriales de Pdf. Cada enfoque tiene ventajas y desventajas. Por ejemplo, si el Metafile se convierte a PNG, entonces puede haber alguna pérdida de calidad durante la escalabilidad del documento resultante. Si el Metafile se convierte a gráficos vectoriales de Pdf, entonces pueden surgir problemas de rendimiento en la herramienta de visualización de Pdf.

### Véase También

* interfaz [IPdfOptions](../../ipdfoptions)
* espacio de nombres [Aspose.Slides.Export](../../ipdfoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->