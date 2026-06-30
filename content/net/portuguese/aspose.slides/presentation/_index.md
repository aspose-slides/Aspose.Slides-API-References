---
title: Presentation
second_title: Aspose.Sildes para .NET Referência da API
description: Representa uma apresentação do Microsoft PowerPoint.
type: docs
weight: 9570
url: /pt/aspose.slides/presentation/
---
## classe Presentation

Representa uma apresentação do Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Construtores

| Name | Description |
| --- | --- |
| [Presentation](presentation#constructor)() | Este construtor cria uma nova Presentation a partir do zero. A Presentation criada tem um slide vazio. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Este construtor cria uma nova Presentation a partir do zero. A Presentation criada tem um slide vazio. |
| [Presentation](presentation#constructor_2)(Stream) | Este construtor é o mecanismo principal para ler uma Presentation existente. |
| [Presentation](presentation#constructor_4)(string) | Este construtor obtém um caminho de arquivo de origem a partir do qual o conteúdo da Presentation é lido. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Este construtor é o mecanismo principal para ler uma Presentation existente. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Este construtor obtém um caminho de arquivo de origem a partir do qual o conteúdo da Presentation é lido. |

## Propriedades

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Retorna todas as partes de dados personalizados na Presentation. Somente leitura [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Retorna a coleção de todos os arquivos de áudio incorporados na Presentation. Somente leitura [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Retorna a coleção de autores de comentários. Somente leitura [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Obtém ou define a data e hora que substituirão o conteúdo dos campos datetime. Por padrão, a hora de criação deste objeto Presentation. Leitura/gravação DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Retorna os dados personalizados da Presentation. Somente leitura [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Retorna o estilo de texto padrão para formas. Somente leitura [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Retorna a coleção de assinaturas usadas para assinar a Presentation. Somente leitura [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Retorna o objeto DocumentProperties que contém propriedades padrão e personalizadas do documento. Somente leitura [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Representa o número do primeiro slide na Presentation |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Retorna o gerenciador de fontes. Somente leitura [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Retorna o gerenciador atual de HeaderFooter. Somente leitura [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Fornece fácil acesso a todos os hyperlinks contidos em todos os slides da Presentation (não em master, layout, notes). Somente leitura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Retorna a coleção de todas as imagens na Presentation. Somente leitura [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Retorna uma lista de todos os slides de layout definidos na Presentation. Somente leitura [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Retorna o gerenciador do handout master. Somente leitura [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Retorna o gerenciador do notes master. Somente leitura [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Retorna uma lista de todos os master slides definidos na Presentation. Somente leitura [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Retorna o tema mestre. Somente leitura [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Retorna o objeto de tamanho do notes slide. Somente leitura [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Obtém o gerenciador de permissões para esta Presentation. Somente leitura [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Retorna uma lista de todas as seções de slides definidas na Presentation. Somente leitura [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Retorna a coleção de rótulos de sensibilidade aplicados ao documento da Presentation. Somente leitura [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Retorna uma lista de todos os slides definidos na Presentation. Somente leitura [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Retorna as configurações de apresentação de slides para a Presentation. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Retorna o objeto de tamanho do slide. Somente leitura [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Retorna informações sobre o formato a partir do qual a Presentation foi carregada. Somente leitura [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Obtém ou define o projeto VBA com macros da Presentation. Leitura/gravação [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Retorna a coleção de todos os arquivos de vídeo incorporados na Presentation. Somente leitura [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Obtém as propriedades de visualização de toda a Presentation. Somente leitura [`IViewProperties`](../iviewproperties). |

## Métodos

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Libera todos os recursos usados por este objeto Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Retorna objetos Image para todos os slides de uma Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Retorna objetos Image em miniatura para slides especificados de uma Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Retorna objetos Image em miniatura para todos os slides de uma Presentation com o tamanho especificado. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Retorna objetos Image em miniatura para todos os slides de uma Presentation com escala personalizada. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Retorna objetos Image em miniatura para slides especificados de uma Presentation com o tamanho especificado. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Retorna objetos Image em miniatura para slides especificados de uma Presentation com escala personalizada. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Retorna um Slide, MasterSlide ou LayoutSlide por Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Realça todas as correspondências da expressão regular com a cor especificada. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Realça todas as correspondências do texto de exemplo com a cor especificada. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Realça todas as correspondências do texto de exemplo com a cor especificada. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Une runs com a mesma formatação em todos os parágrafos em todas as formas aceitáveis em todos os slides. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Substitui todas as correspondências da expressão regular pela string especificada. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Substitui todas as ocorrências do texto especificado por outro texto especificado. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Salva todos os slides de uma Presentation em um conjunto de arquivos que representam a marcação XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Salva todos os slides de uma Presentation em um stream no formato especificado. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Salva todos os slides de uma Presentation em um arquivo com o formato especificado. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Salva slides especificados de uma Presentation em um stream no formato especificado mantendo a numeração de páginas. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Salva todos os slides de uma Presentation em um stream no formato especificado e com opções adicionais. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Salva slides especificados de uma Presentation em um arquivo com o formato especificado mantendo a numeração de páginas. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Salva slides especificados de uma Presentation em um stream no formato especificado mantendo a numeração de páginas. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Salva slides especificados de uma Presentation em um arquivo com o formato especificado mantendo a numeração de páginas. |

### Exemplos

O exemplo a seguir mostra como criar uma Presentation do PowerPoint.

```csharp
[C#]
// Instancia um objeto Presentation que representa um arquivo de apresentação
using (Presentation presentation = new Presentation())
{
    // Obtém o primeiro slide
    ISlide slide = presentation.Slides[0];
    // Adiciona uma autoshape do tipo linha
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Salva o arquivo de apresentação.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

O exemplo a seguir mostra como abrir e salvar uma Presentation.

```csharp
[C#]
// Carregue qualquer arquivo suportado na Presentation, por exemplo, ppt, pptx, odp etc.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Salve o arquivo de apresentação.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Ver Também

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->