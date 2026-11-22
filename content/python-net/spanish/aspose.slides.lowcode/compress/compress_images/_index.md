---
title: compress_images method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Reduce la resolución de las imágenes en la presentación y elimina sus áreas recortadas, de forma similar a la función "Compress Pictures" de PowerPoint aplicada a todas las imágenes. Se procesan las imágenes en diapositivas, diapositivas de diseño y diapositivas maestras, incluidas las imágenes dentro de formas agrupadas y los rellenos de imágenes de las formas.


```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation) | The presentation to process. |
| resolution | [`PicturesCompression`](/slides/python-net/es/aspose.slides.export/picturescompression) | Resolución objetivo relativa al tamaño con el que se muestra cada imagen.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/es/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) deja las imágenes sin cambios. |

### Observaciones

Las imágenes que ya están en la resolución objetivo o por debajo de ella se dejan sin cambios; nunca se aumenta su escala.

No se procesan: fondos de diapositivas, rellenos de celdas de tabla, gráficos, SmartArt, imágenes GIF (para preservar la animación), imágenes SVG y metarchivo (EMF/WMF).

Las áreas recortadas se eliminan de forma permanente y no pueden restaurarse en PowerPoint.

### Excepciones

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` es `None`. |



### Ver también
* clase [`Compress`](/slides/python-net/es/aspose.slides.lowcode/compress)
* clase [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation)
* enumeración [`PicturesCompression`](/slides/python-net/es/aspose.slides.export/picturescompression)
* módulo [`aspose.slides.lowcode`](/slides/python-net/es/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)