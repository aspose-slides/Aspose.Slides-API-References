---
title: save_metafiles_as_png property
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png propiedad
True to convert all metafiles used in a presentation to the PNG images.
            Lectura/escritura **bool**.

### Observaciones

Default is **true** .
            El documento Pdf puede contener gráficos vectoriales e imágenes raster. 
            Si SaveMetafilesAsPng está configurado a true entonces la imagen Metafile de origen se convierte al formato Png y se guarda en Pdf como una imagen raster. 
            Si SaveMetafilesAsPng está configurado a false entonces el Metafile de origen se convierte a gráficos vectoriales Pdf. 
            Cada enfoque tiene ventajas y desventajas. 
            Por ejemplo, si Metafile se convierte a PNG, entonces es posible una pérdida de calidad durante el escalado del documento resultante. 
            Si Metafile se convierte a gráficos vectoriales Pdf, entonces pueden producirse problemas de rendimiento en la herramienta de visualización Pdf.

### Definición:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### Ver también
* clase [`PdfOptions`](/slides/python-net/es/aspose.slides.export/pdfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)