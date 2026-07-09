---
title: IPictureFillFormat
second_title: Aspose.Sildes para .NET Referência da API
description: Representa um estilo de preenchimento de imagem.
type: docs
weight: 6650
url: /pt/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat interface

Representa um estilo de preenchimento de imagem.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Permite obter a interface IFillParamSource base. Somente leitura [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Retorna ou define o número de porcentagens da altura real da imagem que são recortadas na parte inferior da imagem. Leitura/gravação Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Retorna ou define o número de porcentagens da largura real da imagem que são recortadas na parte esquerda da imagem. Leitura/gravação Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Retorna ou define o número de porcentagens da largura real da imagem que são recortadas na parte direita da imagem. Leitura/gravação Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Retorna ou define o número de porcentagens da altura real da imagem que são recortadas na parte superior da imagem. Leitura/gravação Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Retorna ou define o dpi usado para preencher uma imagem. Leitura/gravação Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Retorna a imagem. Somente leitura [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Retorna ou define o modo de preenchimento da imagem. Leitura/gravação [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Retorna ou define a borda inferior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. Uma porcentagem positiva indica um recuo, enquanto uma porcentagem negativa indica um extrusão. Leitura/gravação Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Retorna ou define a borda esquerda do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. Uma porcentagem positiva indica um recuo, enquanto uma porcentagem negativa indica um extrusão. Leitura/gravação Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Retorna ou define a borda direita do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. Uma porcentagem positiva indica um recuo, enquanto uma porcentagem negativa indica um extrusão. Leitura/gravação Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Retorna ou define a borda superior do retângulo de preenchimento que é definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. Uma porcentagem positiva indica um recuo, enquanto uma porcentagem negativa indica um extrusão. Leitura/gravação Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Retorna ou define como a textura é alinhada dentro da forma. Esta configuração controla o ponto de partida do padrão de textura e como ele se repete ao longo da forma. Leitura/gravação [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Inverte o bloco de textura ao redor do seu eixo horizontal, vertical ou ambos. Leitura/gravação [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Retorna ou define o deslocamento horizontal da textura a partir da origem da forma em pontos. Um valor positivo move a textura para a direita, enquanto um valor negativo move-a para a esquerda. Leitura/gravação Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Retorna ou define o deslocamento vertical da textura a partir da origem da forma em pontos. Um valor positivo move a textura para baixo, enquanto um valor negativo move-a para cima. Leitura/gravação Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Retorna ou define a escala horizontal do preenchimento de textura como porcentagem. Leitura/gravação Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Retorna ou define a escala vertical do preenchimento de textura como porcentagem. Leitura/gravação Single. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Exclui áreas recortadas da imagem de preenchimento. |

### Veja Também

* interface [IFillParamSource](../ifillparamsource)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->