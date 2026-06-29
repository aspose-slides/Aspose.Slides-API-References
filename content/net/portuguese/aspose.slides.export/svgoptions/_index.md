---
title: SVGOptions
second_title: Referência da API Aspose.Sildes para .NET
description: Representa opções SVG.
type: docs
weight: 4410
url: /pt/aspose.slides.export/svgoptions/
---
## classe SVGOptions

Representa uma opção SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Inicializa uma nova instância da classe SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Inicializa uma nova instância da classe SVGOptions especificando o objeto controlador de incorporação de links. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Retorna as configurações padrão. Somente leitura [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Retorna configurações para a geração do arquivo SVG mais simples e menor. Somente leitura [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Retorna configurações para a geração do arquivo SVG mais preciso. Somente leitura [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Retorna ou define a fonte usada caso a fonte de origem não seja encontrada. Leitura/Gravação String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se verdadeiro, as partes recortadas serão removidas; se falso, serão serializadas no documento (o que pode levar a um arquivo maior). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Determina se o texto 3D está desativado no SVG. Leitura/Gravação Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como `true`, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Desativa a divisão dos gradientes FromCornerX e FromCenter. Leitura/Gravação Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | O SVG 1.1 não possui capacidade de definir inserções para marcadores. O mecanismo de gravação SVG do Aspose.Slides tem uma solução alternativa para esse problema: ele recorta a extremidade da linha com seta, de modo que a linha não se sobreponha aos marcadores. Esta opção desativa esse comportamento. Leitura/Gravação Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Determina uma forma de lidar com fontes carregadas externamente. Leitura/Gravação [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Retorna ou define o estilo visual do gradiente. Leitura/Gravação [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Fornece opções que controlam a aparência dos objetos Ink no documento exportado. Somente leitura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Determina a qualidade de codificação JPEG. Leitura/Gravação Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Retorna ou define o limite inferior de resolução para rasterização de metafile. Leitura/Gravação Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Representa o nível de compressão das imagens |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa um objeto de retorno de chamada para salvar atualizações de progresso em percentual. Veja [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Retorna e define uma interface de retorno de chamada que permite ao usuário controlar a conversão de shapes. Leitura/Gravação [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica se deve ignorar hyperlinks com chamadas JavaScript ao salvar a apresentação. Leitura/Gravação Boolean. O valor padrão é **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Determina se deve realizar a rotação especificada da forma ao renderizar ou não. Leitura/Gravação Boolean. O valor padrão é true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Determina se a caixa de texto será incluída em uma área de renderização ou não. Leitura/Gravação Boolean. O valor padrão é false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Determina se o texto em um slide será salvo como gráficos. Leitura/Gravação Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/Gravação [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Veja Também

* classe [SaveOptions](../saveoptions)
* interface [ISVGOptions](../isvgoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->