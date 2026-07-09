---
title: PdfOptions
second_title: Aspose.Sildes para .NET Referência da API
description: Fornece opções que controlam como uma apresentação é salva no formato Pdf.
type: docs
weight: 4330
url: /pt/aspose.slides.export/pdfoptions/
---
## PdfOptions classe

Fornece opções que controlam como uma apresentação é salva no formato Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfOptions](pdfoptions)() | Construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Contém um conjunto de sinalizadores que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que o Aspose.Slides deve considerar comuns. Leitura/gravação String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Aplica a cor transparente especificada a uma imagem se `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. Se definido como Boolean.true, para cada imagem na apresentação o algoritmo de compressão mais adequado será escolhido, o que levará a um tamanho menor do documento PDF resultante. A seleção da melhor taxa de compressão de imagem é computacionalmente cara e consome memória RAM adicional, e esta opção tem o valor Boolean.false por padrão. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Nível de conformidade desejado para o documento PDF gerado. Leitura/gravação [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Retorna ou define a fonte usada caso a fonte de origem não seja encontrada. Leitura/gravação String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | Verdadeiro para desenhar uma moldura preta ao redor de cada slide. Leitura/gravação Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Determina se todos os caracteres da fonte devem ser incorporados ou apenas um subconjunto usado. Leitura/gravação Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Determina se o Aspose.Slides incorporará fontes comuns para texto ASCII (faixa de códigos 33..127). Fontes para códigos de caracteres superiores a 127 são sempre incorporadas. A lista de fontes comuns inclui as 14 fontes base do PDF e fontes adicionais especificadas pelo usuário. Leitura/gravação Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Retorna ou define o estilo visual do degradê. Leitura/gravação [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Obtém ou define a cor transparente da imagem. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Leitura/gravação Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Fornece opções que controlam a aparência dos objetos Ink no documento exportado. Somente leitura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. Leitura/gravação Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Define a senha do usuário para proteger o documento PDF. Leitura/gravação String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa um objeto de retorno de chamada para atualizações de progresso de salvamento em porcentagem. Veja [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não suporta estilo negrito. Esta abordagem pode melhorar a qualidade do texto no PDF resultante para certas fontes. Leitura/gravação Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | Verdadeiro para converter todos os metarquivos usados em uma apresentação em imagens PNG. Leitura/gravação Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica se deve pular hiperlinks com chamadas JavaScript ao salvar a apresentação. Leitura/gravação Boolean. O valor padrão é **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Especifica o tipo de compressão a ser usado para todo o conteúdo textual do documento. Leitura/gravação [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/gravação [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exemplos

O exemplo a seguir mostra como converter PowerPoint para PDF com opções personalizadas.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instancia a classe PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Define a qualidade Jpeg
	pdfOptions.JpegQuality = 90;
	// Define o comportamento para metafiles
	pdfOptions.SaveMetafilesAsPng = true;
	// Define o nível de compressão de texto
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Define o padrão PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Salva a apresentação como PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

O exemplo a seguir mostra como converter PowerPoint para PDF com slides ocultos.

```csharp
[C#]
// Instancia a classe Presentation que representa um arquivo PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instancia a classe PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Adiciona slides ocultos
	pdfOptions.ShowHiddenSlides = true;
	// Salva a apresentação como PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

O exemplo a seguir mostra como converter PowerPoint para PDF protegido por senha.

```csharp
[C#]
// Instancia um objeto Presentation que representa um arquivo PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Instancia a classe PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Define a senha PDF e as permissões de acesso
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Salva a apresentação como PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

O exemplo a seguir mostra como converter PowerPoint para PDF com notas.

```csharp
[C#]
// Instancia um objeto Presentation que representa um arquivo de apresentação
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Definindo o tipo e o tamanho do slide
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Veja Também

* classe [SaveOptions](../saveoptions)
* interface [IPdfOptions](../ipdfoptions)
* espaço de nomes [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->