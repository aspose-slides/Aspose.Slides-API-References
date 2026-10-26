---
title: PPImage class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ppimage/
---
## PPImage clase

Representa una imagen en una presentación.

El tipo PPImage expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/es/aspose.slides/ppimage/binary_data/) | Devuelve una copia de los datos de una imagen.<br/>            Solo lectura **int**[]. |
| [`image`](/slides/python-net/es/aspose.slides/ppimage/image/) | Devuelve una copia de una imagen.<br/>            Solo lectura [`IImage`](/slides/python-net/es/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/es/aspose.slides/ppimage/svg_image/) | Devuelve o establece el objeto ISvgImage [`ISvgImage`](/slides/python-net/es/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/es/aspose.slides/ppimage/content_type/) | Devuelve un tipo MIME de una imagen, codificado en [`PPImage.binary_data`](/slides/python-net/es/aspose.slides/ppimage/binary_data).<br/>            Solo lectura **str**. |
| [`width`](/slides/python-net/es/aspose.slides/ppimage/width/) | Devuelve el ancho de una imagen.<br/>            Solo lectura **int**. |
| [`height`](/slides/python-net/es/aspose.slides/ppimage/height/) | Devuelve la altura de una imagen.<br/>            Solo lectura **int**. |
| [`x`](/slides/python-net/es/aspose.slides/ppimage/x/) | Devuelve el desplazamiento X de una imagen.<br/>            Solo lectura **int**. |
| [`y`](/slides/python-net/es/aspose.slides/ppimage/y/) | Devuelve el desplazamiento Y de una imagen.<br/>            Solo lectura **int**. |

## Métodos

| Method | Description |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/es/aspose.slides/ppimage/replace_image/#bytes) | Reemplaza los datos de la imagen.<br/>            Los datos de la nueva imagen.Cuando newImageData parámetro es None. |
| [`replace_image(self, new_image)`](/slides/python-net/es/aspose.slides/ppimage/replace_image/#iimage) | Reemplaza los datos de la imagen. Atención: cuando Image es metafile - será rasterizada. Use ReplaceImage(byte[]) en su lugar<br/>            La nueva imagen.Cuando newImage parámetro es None. |
| [`replace_image(self, new_image)`](/slides/python-net/es/aspose.slides/ppimage/replace_image/#ippimage) | Reemplaza los datos de la imagen.<br/>            El nuevo IPPImage.Cuando newImage parámetro es None. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)