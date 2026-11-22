---
title: compress_presentation method
second_title: Referencia de API Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Reduce el tamaño de una presentación aplicando todos los pasos de compresión disponibles:
            
* Elimina diapositivas master no utilizadas **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Elimina diapositivas de diseño no utilizadas **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Mantiene solo los glifos realmente usados en fuentes incrustadas **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Reduce la resolución de imágenes a 150 DPI y elimina áreas recortadas de las imágenes **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/es/aspose.slides/presentation) | La presentación a comprimir. |

### Observaciones

Para personalizar la compresión, por ejemplo para usar una resolución de imagen diferente o para omitir un paso, llame a los métodos listados arriba individualmente en lugar de este. Las áreas recortadas de las imágenes se eliminan permanentemente y no pueden restaurarse en PowerPoint.

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` es `None`. |



### Ver también
* clase [`Compress`](/slides/python-net/es/aspose.slides.lowcode/compress)
* clase [`Presentation`](/slides/python-net/es/aspose.slides/presentation)
* módulo [`aspose.slides.lowcode`](/slides/python-net/es/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)