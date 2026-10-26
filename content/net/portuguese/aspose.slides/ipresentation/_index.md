---
title: IPresentation
second_title: Aspose.Sildes para a Referência da API .NET
description: Documento de apresentação
type: docs
weight: 6750
url: /pt/aspose.slides/ipresentation/
---
## IPresentation interface

Documento de apresentação

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Retorna todas as partes de dados personalizados na apresentação. Somente leitura [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Retorna a interface IDisposable. Somente leitura IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Permite obter a interface base IPresentationComponent. Somente leitura [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Retorna a coleção de todos os arquivos de áudio incorporados na apresentação. Somente leitura [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Retorna a coleção de autores de comentários. Somente leitura [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Retorna ou define a data e hora que substituirá o conteúdo dos campos datetime. Hora da criação deste objeto Presentation por padrão. Leitura/gravação DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Retorna os dados personalizados da apresentação. Somente leitura [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Retorna o estilo de texto padrão para formas. Somente leitura [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Retorna a coleção de assinaturas usadas para assinar a apresentação. Somente leitura [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Retorna o objeto DocumentProperties que contém propriedades padrão e personalizadas do documento. Somente leitura [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Representa o número do primeiro slide na apresentação. Leitura/gravação Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Retorna o gerenciador de fontes. Somente leitura [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Retorna o gerenciador HeaderFooter da apresentação. Somente leitura [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Fornece acesso fácil a todos os hyperlinks contidos em todos os slides da apresentação (não nos slides mestre, layout ou notas). Somente leitura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Retorna a coleção de todas as imagens na apresentação. Somente leitura [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Retorna uma lista de todos os slides de layout definidos na apresentação. Somente leitura [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Retorna o gerenciador de mestre de folheto. Somente leitura [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Retorna o gerenciador de mestre de notas. Somente leitura [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Retorna uma lista de todos os slides mestres definidos na apresentação. Somente leitura [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Retorna o tema mestre da apresentação. Somente leitura [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Retorna o objeto de tamanho do slide de notas. Somente leitura [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Obtém o gerenciador de permissões para esta apresentação. Somente leitura [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Retorna uma lista de todas as seções de slides definidas na apresentação. Somente leitura [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Retorna a coleção de rótulos de sensibilidade aplicados ao documento da apresentação. Somente leitura [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Retorna uma lista de todos os slides definidos na apresentação. Somente leitura [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Retorna o objeto de tamanho do slide. Somente leitura [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Retorna informações sobre de qual formato a apresentação foi carregada. Somente leitura [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Obtém o projeto VBA com macros da apresentação. Leitura/gravação [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Retorna a coleção de todos os arquivos de vídeo incorporados na apresentação. Somente leitura [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Obtém as propriedades de visualização amplas da apresentação. Somente leitura [`IViewProperties`](../iviewproperties). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Retorna objetos Image de miniatura para todos os slides de uma apresentação. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Retorna objetos Bitmap de miniatura para slides especificados de uma apresentação. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Retorna objetos Image de miniatura para todos os slides de uma apresentação com o tamanho especificado. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Retorna objetos Image de miniatura para todos os slides de uma apresentação com escala personalizada. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Retorna objetos Image de miniatura para slides especificados de uma apresentação com o tamanho especificado. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Retorna objetos Image de miniatura para slides especificados de uma apresentação com escala personalizada. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Retorna um Slide, MasterSlide ou LayoutSlide por Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Realça todas as correspondências da expressão regular com a cor especificada. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Realça todas as correspondências do texto de exemplo com a cor especificada. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Realça todas as correspondências do texto de exemplo com a cor especificada. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Mescla execuções com a mesma formatação em todos os parágrafos em todas as formas aceitáveis em todos os slides. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Substitui todas as correspondências da expressão regular pela string especificada. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Substitui todas as ocorrências do texto especificado por outro texto especificado. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Salva todos os slides de uma apresentação em um conjunto de arquivos que representam marcação XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Salva todos os slides de uma apresentação em um fluxo no formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Salva todos os slides de uma apresentação em um arquivo com o formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Salva slides especificados de uma apresentação em um fluxo no formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Salva todos os slides de uma apresentação em um fluxo no formato especificado e com opções adicionais. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Salva slides especificados de uma apresentação em um arquivo com o formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Salva todos os slides de uma apresentação em um arquivo com o formato especificado e com opções adicionais. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Salva slides especificados de uma apresentação em um fluxo no formato especificado. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Salva slides especificados de uma apresentação em um arquivo com o formato especificado. |

### Veja Também

* interface [IPresentationComponent](../ipresentationcomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->