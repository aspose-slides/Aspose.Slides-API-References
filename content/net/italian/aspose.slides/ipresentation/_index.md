---
title: IPresentation
second_title: Riferimento API Aspose.Sildes per .NET
description: Documento di presentazione
type: docs
weight: 6750
url: /it/aspose.slides/ipresentation/
---
## Interfaccia IPresentation

Documento di presentazione

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Restituisce tutte le parti di dati personalizzati nella presentazione. Solamente lettura [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Restituisce l'interfaccia IDisposable. Solamente lettura IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia di base IPresentationComponent. Solamente lettura [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Restituisce la raccolta di tutti i file audio incorporati nella presentazione. Solamente lettura [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Restituisce la raccolta degli autori dei commenti. Solamente lettura [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Restituisce o imposta la data e l'ora che sostituiranno il contenuto dei campi datetime. Per impostazione predefinita, l'ora di creazione di questo oggetto Presentation. Lettura/scrittura DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Restituisce i dati personalizzati della presentazione. Solamente lettura [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Restituisce lo stile di testo predefinito per le forme. Solamente lettura [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Restituisce la raccolta delle firme usate per firmare la presentazione. Solamente lettura [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Restituisce l'oggetto DocumentProperties che contiene le proprietà standard e personalizzate del documento. Solamente lettura [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Rappresenta il numero della prima diapositiva nella presentazione. Lettura/scrittura Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Restituisce il gestore dei caratteri. Solamente lettura [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Restituisce il gestore HeaderFooter della presentazione. Solamente lettura [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Fornisce un accesso facile a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (esclusi i master, i layout e le diapositive note). Solamente lettura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Restituisce la raccolta di tutte le immagini nella presentazione. Solamente lettura [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Restituisce un elenco di tutte le diapositive di layout definite nella presentazione. Solamente lettura [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Restituisce il gestore del master delle dispense. Solamente lettura [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Restituisce il gestore del master delle note. Solamente lettura [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Restituisce un elenco di tutte le diapositive master definite nella presentazione. Solamente lettura [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Restituisce il tema master della presentazione. Solamente lettura [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Restituisce l'oggetto dimensione della diapositiva delle note. Solamente lettura [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Restituisce il gestore delle autorizzazioni per questa presentazione. Solamente lettura [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Restituisce un elenco di tutte le sezioni di diapositive definite nella presentazione. Solamente lettura [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Restituisce la raccolta delle etichette di sensibilità applicate al documento della presentazione. Solamente lettura [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Restituisce un elenco di tutte le diapositive definite nella presentazione. Solamente lettura [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Restituisce l'oggetto dimensione della diapositiva. Solamente lettura [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Restituisce informazioni sul formato da cui è stata caricata la presentazione. Solamente lettura [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Restituisce il progetto VBA con le macro della presentazione. Lettura/scrittura [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Restituisce la raccolta di tutti i file video incorporati nella presentazione. Solamente lettura [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Restituisce le proprietà di visualizzazione dell'intera presentazione. Solamente lettura [`IViewProperties`](../iviewproperties). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Restituisce oggetti Thumbnail Bitmap per le diapositive specificate di una presentazione. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con dimensione specificata. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con scala personalizzata. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con dimensione specificata. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con scala personalizzata. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Restituisce una Slide, MasterSlide o LayoutSlide per Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Unisce i run con la stessa formattazione in tutti i paragrafi di tutte le forme ammissibili in tutte le diapositive. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano markup XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Salva tutte le diapositive di una presentazione in un file con il formato specificato. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato e con opzioni aggiuntive. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Salva le diapositive specificate di una presentazione in un file con il formato specificato. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Salva le diapositive specificate di una presentazione in un file con il formato specificato. |

### Vedi anche

* interfaccia [IPresentationComponent](../ipresentationcomponent)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->