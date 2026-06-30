---
title: TiffOptions
second_title: Aspose.Sildes para .NET Referência da API
description: Fornece opções que controlam como uma apresentação é salva no formato TIFF.
type: docs
weight: 4550
url: /pt/aspose.slides.export/tiffoptions/
---
## TiffOptions classe

Fornece opções que controlam como uma apresentação é salva no formato TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TiffOptions](tiffoptions)() | Construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. Esta opção será aplicada somente se [`CompressionType`](./compressiontype) estiver definido como CCITT4 ou CCITT3 Leitura/Gravação [`BlackWhiteConversionMode`](../blackwhiteconversionmode). O padrão é Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Especifica o tipo de compressão. Leitura/Gravação [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Retorna ou define a fonte usada caso a fonte de origem não seja encontrada. Leitura/Gravação String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Especifica a resolução horizontal em pontos por polegada. Leitura/Gravação UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Especifica a resolução vertical em pontos por polegada. Leitura/Gravação UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Retorna ou define o estilo visual do gradiente. Leitura/Gravação [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Especifica o tamanho de uma imagem TIFF gerada. O valor padrão é 0x0, o que significa que os tamanhos das imagens geradas serão calculados com base no valor do tamanho dos slides da apresentação. Leitura/Gravação Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Fornece opções que controlam a aparência de objetos Ink no documento exportado. Somente leitura [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Especifica o formato de pixel para as imagens geradas. Leitura/Gravação [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa um objeto de callback para atualizações de progresso de gravação em percentual. Veja [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Leitura/Gravação Boolean. O valor padrão é **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/Gravação [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exemplos

O exemplo a seguir mostra como converter PowerPoint para TIFF com tamanho padrão.

```csharp
[C#]
// Instanciar um objeto Presentation que representa um arquivo de apresentação
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Salvando a apresentação como documento TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

O exemplo a seguir mostra como converter PowerPoint para TIFF com tamanho personalizado.

```csharp
[C#]
// Instanciar um objeto Presentation que representa um arquivo Presentation
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Instanciar a classe TiffOptions
    TiffOptions opts = new TiffOptions();
    // Definindo o tipo de compressão
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Tipos de compressão
    // Default - Especifica o esquema de compressão padrão (LZW).
    // None - Especifica nenhuma compressão.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // A profundidade depende do tipo de compressão e não pode ser definida manualmente.
    // A unidade de resolução é sempre igual a “2” (pontos por polegada)
    // Definindo DPI da imagem
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Definir tamanho da imagem
    opts.ImageSize = new Size(1728, 1078);
    // Salvar a apresentação como TIFF com o tamanho de imagem especificado
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

O exemplo a seguir mostra como converter PowerPoint para TIFF com formato de pixel de imagem personalizado.

```csharp
[C#]
// Instanciar um objeto Presentation que representa um arquivo Presentation
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat contém os seguintes valores (conforme pode ser visto na documentação):
    Format1bppIndexed; // 1 bits por pixel, indexado.
    Format4bppIndexed; // 4 bits por pixel, indexado.
    Format8bppIndexed; // 8 bits por pixel, indexado.
    Format24bppRgb; // 24 bits por pixel, RGB.
    Format32bppArgb; // 32 bits por pixel, ARGB.
    */
    // Salvar a apresentação como TIFF com o tamanho de imagem especificado
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Veja Também

* classe [SaveOptions](../saveoptions)
* interface [ITiffOptions](../itiffoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->