---
title: save_metafiles_as_png property
second_title: Aspose.Slides para Python a través de la referencia de API .NET
description: 
type: docs
url: /es/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png propiedad
True para convertir todos los metafiles usados en una presentación a las imágenes PNG.
            Lectura/escritura **bool**.

### Observaciones

El valor predeterminado es **true** .
            Un documento Pdf puede contener gráficos vectoriales e imágenes raster. 
            Si SaveMetafilesAsPng está configurado en true, entonces la imagen Metafile de origen se convierte al formato Png y se guarda en Pdf como una imagen raster. 
            Si SaveMetafilesAsPng está configurado en false, entonces el Metafile de origen se convierte a gráficos vectoriales Pdf. 
            Cada enfoque tiene ventajas y desventajas. 
            Por ejemplo, si Metafile se convierte a PNG, es posible que se produzca cierta pérdida de calidad al escalar el documento resultante. 
            Si Metafile se convierte a gráficos vectoriales Pdf, es posible que haya problemas de rendimiento en la herramienta de visualización Pdf.

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
* clase [`IPdfOptions`](/slides/python-net/es/aspose.slides.export/ipdfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/es/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)