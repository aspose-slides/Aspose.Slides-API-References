---
title: PictureFillFormat
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um estilo de preenchimento de imagem.
type: docs
weight: 9370
url: /pt/aspose.slides/picturefillformat/
---
## PictureFillFormat classe

Representa um estilo de preenchimento de imagem.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obter a interface base IPresentationComponent. Somente leitura [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Retorna ou define o número de porcentagem da altura real da imagem que é recortada na parte inferior da imagem. Leitura/gravação Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Retorna ou define o número de porcentagem da largura real da imagem que é recortada na parte esquerda da imagem. Leitura/gravação Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Retorna ou define o número de porcentagem da largura real da imagem que é recortada na parte direita da imagem. Leitura/gravação Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Retorna ou define o número de porcentagem da altura real da imagem que é recortada na parte superior da imagem. Leitura/gravação Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Retorna ou define o DPI usado para preencher uma imagem. Leitura/gravação Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Retorna a imagem. Somente leitura [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Retorna ou define o modo de preenchimento da imagem. Leitura/gravação [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Retorna ou define a borda inferior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalimento. Leitura/gravação Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Retorna ou define a borda esquerda do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalimento. Leitura/gravação Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Retorna ou define a borda direita do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalimento. Leitura/gravação Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Retorna ou define a borda superior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalimento. Leitura/gravação Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Retorna ou define como a textura é alinhada dentro da forma. Esta configuração controla o ponto de partida do padrão de textura e como ele se repete na forma. Leitura/gravação [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Inverte o bloco de textura ao redor de seu eixo horizontal, vertical ou ambos. Leitura/gravação [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Retorna ou define o deslocamento horizontal da textura a partir da origem da forma em pontos. Um valor positivo move a textura para a direita, enquanto um valor negativo a move para a esquerda. Leitura/gravação Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Retorna ou define o deslocamento vertical da textura a partir da origem da forma em pontos. Um valor positivo move a textura para baixo, enquanto um valor negativo a move para cima. Leitura/gravação Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Retorna ou define a escala horizontal do preenchimento da textura como porcentagem. Leitura/gravação Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Retorna ou define a escala vertical do preenchimento da textura como porcentagem. Leitura/gravação Single. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Exclui áreas recortadas da imagem de preenchimento. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara com o objeto especificado. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retorna o código hash. |

### Veja Também

* classe [PVIObject](../pviobject)
* interface [IPictureFillFormat](../ipicturefillformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->