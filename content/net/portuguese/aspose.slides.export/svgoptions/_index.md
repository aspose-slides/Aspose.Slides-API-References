---
title: SVGOptions
second_title: Aspose.Sildes para referência da API .NET
description: Representa opções de SVG.
type: docs
weight: 4450
url: /pt/aspose.slides.export/svgoptions/
---
## SVGOptions classe

Representa opções de SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Inicializa uma nova instância da classe SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Inicializa uma nova instância da classe SVGOptions especificando o objeto controlador de incorporação de link. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Retorna as configurações padrão. Somente leitura [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Retorna configurações para a geração de arquivos SVG mais simples e menores. Somente leitura [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Retorna configurações para a geração de arquivos SVG mais precisos. Somente leitura [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Retorna ou define a fonte usada caso a fonte de origem não seja encontrada. Leitura e gravação String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se verdadeiro, as partes recortadas serão removidas; se falso, serão serializadas no documento (o que pode levar a um arquivo maior). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Determina se o texto 3D está desativado no SVG. Leitura/gravação Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como `true`, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade é definida como `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Desativa a divisão dos gradientes FromCornerX e FromCenter. Leitura/gravação Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | O SVG 1.1 não possui capacidade de definir recuos para marcadores. O mecanismo de gravação SVG da Aspose.Slides tem uma solução alternativa para esse problema: ele recorta o final da linha com a seta, de modo que a linha não sobreponha os marcadores. Esta opção desliga esse comportamento. Leitura/gravação Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Determina um modo de manipular fontes carregadas externamente. Leitura/gravação [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Retorna ou define o estilo visual do gradiente. Leitura/gravação [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Fornece opções que controlam a aparência de objetos Ink no documento exportado. Somente leitura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Determina a qualidade de codificação JPEG. Leitura/gravação Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Retorna ou define o limite inferior de resolução para a rasterização de metafile. Leitura/gravação Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Representa o nível de compressão das imagens |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa um objeto de callback para salvar atualizações de progresso em porcentagem. Veja [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Retorna e define uma interface de callback que permite ao usuário controlar a conversão de forma. Leitura/gravação [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica se deve pular hiperlinks com chamadas JavaScript ao salvar a apresentação. Leitura/gravação Boolean. O valor padrão é **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Determina se deve executar a rotação especificada da forma ao renderizar ou não. Leitura/gravação Boolean. O valor padrão é true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Determina se a caixa de texto será incluída em uma área de renderização ou não. Leitura/gravação Boolean. O valor padrão é false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Determina se o texto em um slide será salvo como gráfico. Leitura/gravação Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/gravação [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Veja Também

* classe [SaveOptions](../saveoptions)
* interface [ISVGOptions](../isvgoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->