---
title: IPdfOptions
second_title: Referência da API Aspose.Sildes para .NET
description: Fornece opções que controlam como uma apresentação é salva no formato Pdf.
type: docs
weight: 3980
url: /pt/aspose.slides.export/ipdfoptions/
---
## IPdfOptions interface

Fornece opções que controlam como uma apresentação é salva no formato Pdf.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Contém um conjunto de sinalizadores que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Consulte [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que o Aspose.Slides deve considerar comuns. Leitura/gravação String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Aplica a cor transparente especificada a uma imagem se `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Retorna a interface ISaveOptions. Somente leitura [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. Se definido como Boolean.true, para cada imagem na apresentação o algoritmo de compressão mais adequado será escolhido, o que resultará em um tamanho menor do documento PDF resultante. A seleção da melhor taxa de compressão de imagem é computacionalmente cara e consome uma quantidade adicional de RAM, e esta opção tem Boolean.false como padrão. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Nível de conformidade desejado para o documento PDF gerado. Leitura/gravação [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True para desenhar uma moldura preta ao redor de cada slide. Leitura/gravação Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Determina se todos os caracteres da fonte devem ser incorporados ou apenas um subconjunto usado. Leitura/gravação Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True para incorporar fontes TrueType para caracteres ASCII 32-127. Fontes para códigos de caracteres superiores a 127 são sempre incorporadas. Leitura/gravação Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Obtém ou define a cor transparente da imagem. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Leitura/gravação Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Fornece opções que controlam a aparência dos objetos Ink no documento exportado. Somente leitura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. Leitura/gravação Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Definindo a senha do usuário para proteger o documento PDF. Leitura/gravação String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indica se o texto deve ser rasterizado como bitmap e salvo no PDF quando a fonte não suporta estilo negrito. Essa abordagem pode melhorar a qualidade do texto no PDF resultante para determinadas fontes. Leitura/gravação Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True para converter todos os metafiles usados em uma apresentação em imagens PNG. Leitura/gravação Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento. Leitura/gravação [`PdfTextCompression`](../pdftextcompression). |

### Ver Também

* interface [ISaveOptions](../isaveoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->