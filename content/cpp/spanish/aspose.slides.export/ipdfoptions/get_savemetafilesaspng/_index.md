---
title: get_SaveMetafilesAsPng()
second_title: Referencia de la API de Aspose.Slides para C++
description: True para convertir todos los metafiles utilizados en una presentación a imágenes PNG. Leer bool.
type: docs
weight: 287
url: /es/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() método


True para convertir todos los metafiles utilizados en una presentación a imágenes PNG. Leer **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Observaciones


Default es **true**. El documento Pdf puede contener gráficos vectoriales e imágenes raster. Si SaveMetafilesAsPng está configurado en true entonces la imagen Metafile de origen se convierte al formato Png y se guarda en Pdf como una imagen raster. Si SaveMetafilesAsPng está configurado en false entonces el Metafile de origen se convierte en gráficos vectoriales Pdf. Cada enfoque tiene ventajas y desventajas. Por ejemplo, si el Metafile se convierte a PNG, entonces es posible una pérdida de calidad durante el escalado del documento resultante. Si el Metafile se convierte a gráficos vectoriales Pdf, entonces pueden producirse problemas de rendimiento en la herramienta de visualización Pdf. 
## Véase también

* Clase [IPdfOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)