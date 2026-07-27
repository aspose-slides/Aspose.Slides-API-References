---
title: get_SaveMetafilesAsPng()
second_title: Referencia de API de Aspose.Slides para C++
description: True para convertir todos los metaficheros usados en una presentación a imágenes PNG. Leer bool.
type: docs
weight: 326
url: /es/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() método

True para convertir todos los metaficheros usados en una presentación a imágenes PNG. Leer **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Observaciones

El valor predeterminado es **true**. Un documento Pdf puede contener gráficos vectoriales e imágenes raster. Si SaveMetafilesAsPng está configurado en true entonces la imagen Metafile de origen se convierte al formato Png y se guarda en Pdf como una imagen raster. Si SaveMetafilesAsPng está configurado en false entonces la Metafile de origen se convierte a gráficos vectoriales Pdf. Cada enfoque tiene ventajas y desventajas. Por ejemplo, si la Metafile se convierte a PNG, entonces es posible una pérdida de calidad durante el escalado del documento resultante. Si la Metafile se convierte a gráficos vectoriales Pdf, entonces pueden producirse problemas de rendimiento en la herramienta de visualización Pdf. 

## Ver también

* Clase [PdfOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)