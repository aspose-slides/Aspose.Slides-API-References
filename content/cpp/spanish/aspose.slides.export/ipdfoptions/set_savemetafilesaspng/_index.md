---
title: set_SaveMetafilesAsPng()
second_title: Referencia de la API de Aspose.Slides para C++
description: True para convertir todos los metafiles usados en una presentación a imágenes PNG. Escriba bool.
type: docs
weight: 300
url: /es/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) método

True para convertir todos los metafiles usados en una presentación a imágenes PNG. Escriba **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Observaciones

El valor predeterminado es **true**. Un documento Pdf puede contener gráficos vectoriales y imágenes raster. Si SaveMetafilesAsPng se establece en true, entonces la imagen Metafile de origen se convierte al formato Png y se guarda en Pdf como una imagen raster. Si SaveMetafilesAsPng se establece en false, entonces el Metafile de origen se convierte en gráficos vectoriales Pdf. Cada enfoque tiene ventajas y desventajas. Por ejemplo, si el Metafile se convierte a PNG, entonces es posible una cierta pérdida de calidad durante el escalado del documento resultante. Si el Metafile se convierte a gráficos vectoriales Pdf, entonces pueden presentarse problemas de rendimiento en la herramienta de visualización Pdf.

## Ver también

* Clase [IPdfOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)