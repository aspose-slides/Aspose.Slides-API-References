---
title: Compress class
second_title: Referencia de la API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides.lowcode/compress/
---
## Compress clase

Representa un grupo de métodos destinados a comprimir [`Presentation`](/slides/python-net/es/aspose.slides/presentation).

El tipo Compress expone los siguientes miembros:

## Métodos

| Método | Descripción |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/es/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Reduce el tamaño de una presentación aplicando todos los pasos de compresión disponibles:<br/>            <br/>* Elimina diapositivas maestras no utilizadas **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Elimina diapositivas de diseño no utilizadas **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Conserva solo los glifos realmente usados en fuentes incrustadas **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Reduce la resolución de imágenes a 150 DPI y elimina áreas recortadas de las imágenes **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/es/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Realiza la compresión del [`Presentation`](/slides/python-net/es/aspose.slides/presentation) eliminando diapositivas maestras no utilizadas. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/es/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Realiza la compresión del [`Presentation`](/slides/python-net/es/aspose.slides/presentation) eliminando diapositivas de diseño no utilizadas. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/es/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Realiza la compresión del [`Presentation`](/slides/python-net/es/aspose.slides/presentation) eliminando caracteres no utilizados de fuentes incrustadas. |
| [`compress_images(presentation, resolution)`](/slides/python-net/es/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Reduce la resolución de las imágenes en la presentación y elimina sus áreas recortadas,<br/>            similar a la función "Compress Pictures" de PowerPoint aplicada a todas las imágenes.<br/>            Se procesan las imágenes en diapositivas, diapositivas de diseño y diapositivas maestras, incluidas las imágenes dentro de formas agrupadas<br/>            y los rellenos de imagen de las formas. |

### Ver también
* clase [`Presentation`](/slides/python-net/es/aspose.slides/presentation)
* módulo [`aspose.slides.lowcode`](/slides/python-net/es/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)