---
title: Presentation
second_title: Aspose.Sildes para .NET Referência da API
description: Representa uma apresentação do Microsoft PowerPoint.
type: docs
weight: 9590
url: /pt/aspose.slides/presentation/
---
## Presentation classe

Representa uma apresentação do Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Presentation](presentation#constructor)() | Este construtor cria uma nova apresentação a partir do zero. A apresentação criada tem um slide vazio. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Este construtor cria uma nova apresentação a partir do zero. A apresentação criada tem um slide vazio. |
| [Presentation](presentation#constructor_2)(Stream) | Este construtor é o principal mecanismo para ler uma apresentação existente. |
| [Presentation](presentation#constructor_4)(string) | Este construtor obtém o caminho do arquivo fonte a partir do qual o conteúdo da apresentação é lido. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Este construtor é o principal mecanismo para ler uma apresentação existente. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Este construtor obtém o caminho do arquivo fonte a partir do qual o conteúdo da apresentação é lido. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Retorna todas as partes de dados personalizados na apresentação. Somente leitura [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Retorna a coleção de todos os arquivos de áudio incorporados na apresentação. Somente leitura [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Retorna a coleção de autores de comentários. Somente leitura [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Obtém ou define a data e hora que substituirá o conteúdo dos campos datetime. Hora da criação deste objeto Presentation por padrão. Leitura/gravação DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Retorna os dados personalizados da apresentação. Somente leitura [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Retorna o estilo de texto padrão para formas. Somente leitura [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Retorna a coleção de assinaturas usadas para assinar a apresentação. Somente leitura [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Retorna o objeto DocumentProperties que contém propriedades de documento padrão e personalizadas. Somente leitura [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Representa o número do primeiro slide na apresentação |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Retorna o gerenciador de fontes. Somente leitura [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Retorna o gerenciador real de HeaderFooter. Somente leitura [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Fornece acesso fácil a todos os hyperlinks contidos em todos os slides da apresentação (não nos slides mestre, layout, notas). Somente leitura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Retorna a coleção de todas as imagens na apresentação. Somente leitura [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Retorna uma lista de todos os slides de layout definidos na apresentação. Somente leitura [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Retorna o gerenciador de mestre de folheto. Somente leitura [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Retorna o gerenciador de mestre de notas. Somente leitura [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Retorna uma lista de todos os slides mestre definidos na apresentação. Somente leitura [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Retorna o tema mestre. Somente leitura [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Retorna o objeto de tamanho do slide de notas. Somente leitura [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Obtém o gerenciador de permissões para esta apresentação. Somente leitura [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Retorna uma lista de todas as seções de slides definidas na apresentação. Somente leitura [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Retorna a coleção de rótulos de sensibilidade aplicados ao documento da apresentação. Somente leitura [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Retorna uma lista de todos os slides definidos na apresentação. Somente leitura [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Retorna as configurações de apresentação de slides para a apresentação. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Retorna o objeto de tamanho do slide. Somente leitura [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Retorna informações sobre o formato a partir do qual a apresentação foi carregada. Somente leitura [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Obtém ou define o projeto VBA com macros da apresentação. Leitura/gravação [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Retorna a coleção de todos os arquivos de vídeo incorporados na apresentação. Somente leitura [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Obtém propriedades de visualização da apresentação. Somente leitura [`IViewProperties`](../iviewproperties). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Libera todos os recursos usados por este objeto Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Retorna objetos Image para todos os slides de uma apresentação. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Retorna objetos Thumbnail Image para slides especificados de uma apresentação. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Retorna objetos Thumbnail Image para todos os slides de uma apresentação com o tamanho especificado. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Retorna objetos Thumbnail Image para todos os slides de uma apresentação com dimensionamento personalizado. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Retorna objetos Thumbnail Image para slides especificados de uma apresentação com o tamanho especificado. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Retorna objetos Thumbnail Image para slides especificados de uma apresentação com dimensionamento personalizado. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Retorna um Slide, MasterSlide ou LayoutSlide por Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Realça todas as correspondências da expressão regular com a cor especificada. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Realça todas as correspondências do texto de exemplo com a cor especificada. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Realça todas as correspondências do texto de exemplo com a cor especificada. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Une execuções com a mesma formatação em todos os parágrafos em todas as formas aceitáveis em todos os slides. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Substitui todas as correspondências da expressão regular pela string especificada. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Substitui todas as ocorrências do texto especificado por outro texto especificado. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Salva todos os slides de uma apresentação em um conjunto de arquivos representando marcação XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Salva todos os slides de uma apresentação em um fluxo no formato especificado. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Salva todos os slides de uma apresentação em um arquivo com o formato especificado. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Salva slides especificados de uma apresentação em um fluxo no formato especificado mantendo o número da página. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Salva todos os slides de uma apresentação em um fluxo no formato especificado e com opções adicionais. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Salva slides especificados de uma apresentação em um arquivo com o formato especificado mantendo o número da página. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Salva slides especificados de uma apresentação em um fluxo no formato especificado mantendo o número da página. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Salva slides especificados de uma apresentação em um arquivo com o formato especificado mantendo o número da página. |

### Exemplos

O exemplo a seguir mostra como criar uma apresentação PowerPoint.

```csharp
[C#]
// Instanciar um objeto Presentation que representa um arquivo de apresentação
using (Presentation presentation = new Presentation())
{
    // Obter o primeiro slide
    ISlide slide = presentation.Slides[0];
    // Adicionar uma autoforma do tipo linha
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Salvar o arquivo de apresentação.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

O exemplo a seguir mostra como abrir e salvar uma apresentação.

```csharp
[C#]
// Carregar qualquer arquivo suportado no Presentation, por exemplo ppt, pptx, odp etc.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Salvar o arquivo de apresentação.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Veja Também

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->