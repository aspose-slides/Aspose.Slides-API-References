---
title: PPImage class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/ppimage/
---
## PPImage classe

Representa uma imagem em uma apresentação.

O tipo PPImage expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`binary_data`](/slides/python-net/pt/aspose.slides/ppimage/binary_data/) | Retorna uma cópia dos dados de uma imagem.<br/>            Somente leitura **int**[]. |
| [`image`](/slides/python-net/pt/aspose.slides/ppimage/image/) | Retorna uma cópia de uma imagem.<br/>            Somente leitura [`IImage`](/slides/python-net/pt/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/pt/aspose.slides/ppimage/svg_image/) | Retorna ou define o objeto ISvgImage [`ISvgImage`](/slides/python-net/pt/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/pt/aspose.slides/ppimage/content_type/) | Retorna um tipo MIME de uma imagem, codificado em [`PPImage.binary_data`](/slides/python-net/pt/aspose.slides/ppimage/binary_data).<br/>            Somente leitura **str**. |
| [`width`](/slides/python-net/pt/aspose.slides/ppimage/width/) | Retorna a largura de uma imagem.<br/>            Somente leitura **int**. |
| [`height`](/slides/python-net/pt/aspose.slides/ppimage/height/) | Retorna a altura de uma imagem.<br/>            Somente leitura **int**. |
| [`x`](/slides/python-net/pt/aspose.slides/ppimage/x/) | Retorna o deslocamento X de uma imagem.<br/>            Somente leitura **int**. |
| [`y`](/slides/python-net/pt/aspose.slides/ppimage/y/) | Retorna o deslocamento Y de uma imagem.<br/>            Somente leitura **int**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/pt/aspose.slides/ppimage/replace_image/#bytes) | Substitui os dados da imagem.<br/>            Os dados da nova imagem. Quando o parâmetro newImageData for None. |
| [`replace_image(self, new_image)`](/slides/python-net/pt/aspose.slides/ppimage/replace_image/#iimage) | Substitui os dados da imagem. Atenção: quando a Imagem é metafile - será rasterizada. Use ReplaceImage(byte[]) em vez disso<br/>            A nova imagem. Quando o parâmetro newImage for None. |
| [`replace_image(self, new_image)`](/slides/python-net/pt/aspose.slides/ppimage/replace_image/#ippimage) | Substitui os dados da imagem.<br/>            O novo IPPImage. Quando o parâmetro newImage for None. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)