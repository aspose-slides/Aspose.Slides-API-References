---
title: IPictureFillFormat class
second_title: Aspose.Slides para Python via .NET - Referência de API
description: 
type: docs
url: /pt/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat classe

Representa um estilo de preenchimento com imagem.

O tipo IPictureFillFormat expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`dpi`](/slides/python-net/pt/aspose.slides/ipicturefillformat/dpi/) | Retorna ou define o dpi que é usado para preencher uma imagem.<br/>            Leitura/gravação **int**. |
| [`picture_fill_mode`](/slides/python-net/pt/aspose.slides/ipicturefillformat/picture_fill_mode/) | Retorna ou define o modo de preenchimento da imagem.<br/>            Leitura/gravação [`PictureFillMode`](/slides/python-net/pt/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/pt/aspose.slides/ipicturefillformat/picture/) | Retorna a imagem.<br/>            Somente leitura [`ISlidesPicture`](/slides/python-net/pt/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/pt/aspose.slides/ipicturefillformat/crop_left/) | Retorna ou define a quantidade de porcentagem da largura real da imagem que é recortada<br/>            à esquerda da imagem. <br/>            Leitura/gravação **float**. |
| [`crop_top`](/slides/python-net/pt/aspose.slides/ipicturefillformat/crop_top/) | Retorna ou define a quantidade de porcentagem da altura real da imagem que é recortada<br/>            no topo da imagem. <br/>            Leitura/gravação **float**. |
| [`crop_right`](/slides/python-net/pt/aspose.slides/ipicturefillformat/crop_right/) | Retorna ou define a quantidade de porcentagem da largura real da imagem que é recortada<br/>            à direita da imagem. <br/>            Leitura/gravação **float**. |
| [`crop_bottom`](/slides/python-net/pt/aspose.slides/ipicturefillformat/crop_bottom/) | Retorna ou define a quantidade de porcentagem da altura real da imagem que é recortada<br/>            na parte inferior da imagem. <br/>            Leitura/gravação **float**. |
| [`stretch_offset_left`](/slides/python-net/pt/aspose.slides/ipicturefillformat/stretch_offset_left/) | Retorna ou define a borda esquerda do retângulo de preenchimento que é definido por um deslocamento percentual <br/>            a partir da borda esquerda da caixa delimitadora da forma. <br/>            Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um afastamento.<br/>            Leitura/gravação **float**. |
| [`stretch_offset_top`](/slides/python-net/pt/aspose.slides/ipicturefillformat/stretch_offset_top/) | Retorna ou define a borda superior do retângulo de preenchimento que é definido por um deslocamento percentual <br/>            a partir da borda superior da caixa delimitadora da forma. <br/>            Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um afastamento.<br/>            Leitura/gravação **float**. |
| [`stretch_offset_right`](/slides/python-net/pt/aspose.slides/ipicturefillformat/stretch_offset_right/) | Retorna ou define a borda direita do retângulo de preenchimento que é definido por um deslocamento percentual <br/>            a partir da borda direita da caixa delimitadora da forma. <br/>            Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um afastamento.<br/>            Leitura/gravação **float**. |
| [`stretch_offset_bottom`](/slides/python-net/pt/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Retorna ou define a borda inferior do retângulo de preenchimento que é definido por um deslocamento percentual <br/>            a partir da borda inferior da caixa delimitadora da forma. <br/>            Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um afastamento.<br/>            Leitura/gravação **float**. |
| [`tile_offset_x`](/slides/python-net/pt/aspose.slides/ipicturefillformat/tile_offset_x/) | Retorna ou define o deslocamento horizontal da textura a partir da origem da forma em pontos.<br/>             Um valor positivo move a textura para a direita, enquanto um valor negativo a move para a esquerda.<br/>             Leitura/gravação **float**. |
| [`tile_offset_y`](/slides/python-net/pt/aspose.slides/ipicturefillformat/tile_offset_y/) | Retorna ou define o deslocamento vertical da textura a partir da origem da forma em pontos.<br/>             Um valor positivo move a textura para baixo, enquanto um valor negativo a move para cima.<br/>             Leitura/gravação **float**. |
| [`tile_scale_x`](/slides/python-net/pt/aspose.slides/ipicturefillformat/tile_scale_x/) | Retorna ou define a escala horizontal para o preenchimento da textura como uma porcentagem.<br/>             Leitura/gravação **float**. |
| [`tile_scale_y`](/slides/python-net/pt/aspose.slides/ipicturefillformat/tile_scale_y/) | Retorna ou define a escala vertical para o preenchimento da textura como uma porcentagem.<br/>             Leitura/gravação **float**. |
| [`tile_alignment`](/slides/python-net/pt/aspose.slides/ipicturefillformat/tile_alignment/) | Retorna ou define como a textura é alinhada dentro da forma. Esta configuração controla o ponto de partida do padrão de textura e como ele se repete ao longo da forma.<br/>             Leitura/gravação [`RectangleAlignment`](/slides/python-net/pt/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/pt/aspose.slides/ipicturefillformat/tile_flip/) | Inverte o bloco de textura em torno de seu eixo horizontal, vertical ou ambos.<br/>             Leitura/gravação [`TileFlip`](/slides/python-net/pt/aspose.slides/tileflip). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/pt/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/pt/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/pt/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Exclui áreas recortadas da Picture de preenchimento. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)