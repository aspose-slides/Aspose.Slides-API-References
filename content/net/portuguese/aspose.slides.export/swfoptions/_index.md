---
title: SwfOptions
second_title: Aspose.Sildes para .NET Referência da API
description: Fornece opções que controlam como uma apresentação é salva no formato Swf.
type: docs
weight: 4550
url: /pt/aspose.slides.export/swfoptions/
---
## SwfOptions classe

Fornece opções que controlam como uma apresentação é salva no formato Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SwfOptions](swfoptions)() | Construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Especifica se o documento SWF gerado deve ser compactado ou não. O padrão é `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Retorna ou define a fonte usada caso a fonte de origem não seja encontrada. String de leitura e escrita. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Habilita/desabilita o menu de contexto. O padrão é true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Retorna ou define o estilo visual do gradiente. Leitura/gravação [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Especifica a qualidade das imagens JPEG. O padrão é 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Imagem que será exibida como logotipo no canto superior direito do visualizador. A imagem deve ser PNG de 32x64 pixels, caso contrário o logotipo pode ser exibido incorretamente. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Obtém ou define o endereço completo do hyperlink para um logotipo. Tem efeito somente se um [`LogoImageBytes`](./logoimagebytes) for especificado. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa um objeto de callback para atualizações de progresso de salvamento em porcentagem. Veja [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Mostrar/ocultar o painel inferior. Pode ser substituído em flashvars. O padrão é true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Mostrar/ocultar o botão de tela cheia. Pode ser substituído em flashvars. O padrão é true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Mostrar/ocultar o painel esquerdo. Pode ser substituído em flashvars. O padrão é true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Especifica se a borda ao redor das páginas deve ser mostrada. O padrão é true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Mostrar/ocultar o seletor de página. Pode ser substituído em flashvars. O padrão é true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Mostrar/ocultar a seção de busca. Pode ser substituído em flashvars. O padrão é true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Mostrar/ocultar todo o painel superior. Pode ser substituído em flashvars. O padrão é true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Boolean de leitura e escrita. O valor padrão é **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [`ISlidesLayoutOptions`](../islideslayoutoptions). Esta propriedade não suporta atribuição de objetos do tipo [`HandoutLayoutingOptions`](../handoutlayoutingoptions). |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Iniciar com o painel esquerdo aberto. Pode ser substituído em flashvars. O padrão é false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. O padrão é `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura/gravação [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exemplos

O exemplo a seguir mostra como converter PowerPoint para SWF Flash.

```csharp
[C#]
// Instanciar um objeto Presentation que representa um arquivo de apresentação
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Salvar a apresentação e as páginas de anotações
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Veja também

* classe [SaveOptions](../saveoptions)
* interface [ISwfOptions](../iswfoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->