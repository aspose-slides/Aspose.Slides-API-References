---
title: SaveMetafilesAsPng
second_title: Aspose.Sildes para .NET Referencia de la API
description: Verdadero para convertir todos los metafiles utilizados en una presentación a imágenes PNG. Lectura/escritura Booleano.
type: docs
weight: 160
url: /es/aspose.slides.export/ipdfoptions/savemetafilesaspng/
---

## Propiedad IPdfOptions.SaveMetafilesAsPng

Verdadero para convertir todos los metafiles utilizados en una presentación a imágenes PNG. Lectura/escritura Booleano.

```csharp
public bool SaveMetafilesAsPng { get; set; }
```

### Observaciones

El valor predeterminado es **verdadero**. Un documento Pdf puede contener gráficos vectoriales e imágenes de mapa de bits. Si SaveMetafilesAsPng se establece en verdadero, la imagen de Metafile fuente se convierte al formato Png y se guarda en Pdf como una imagen de mapa de bits. Si SaveMetafilesAsPng se establece en falso, entonces el Metafile fuente se convierte en gráficos vectoriales de Pdf. Cada enfoque tiene ventajas y desventajas. Por ejemplo, si el Metafile se convierte a PNG, es posible que haya alguna pérdida de calidad durante el escalado del documento resultante. Si el Metafile se convierte en gráficos vectoriales de Pdf, es posible que haya problemas de rendimiento en la herramienta de visualización de Pdf.

### Véase También

* interfaz [IPdfOptions](../../ipdfoptions)
* espacio de nombres [Aspose.Slides.Export](../../ipdfoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->