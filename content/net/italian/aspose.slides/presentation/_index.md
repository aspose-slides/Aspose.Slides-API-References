---
title: Presentation
second_title: Aspose.Sildes per .NET Riferimento API
description: Rappresenta una presentazione Microsoft PowerPoint.
type: docs
weight: 9610
url: /it/aspose.slides/presentation/
---
## Presentation classe

Rappresenta una presentazione Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Presentation](presentation#constructor)() | Questo costruttore crea una nuova presentazione da zero. La presentazione creata ha una diapositiva vuota. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Questo costruttore crea una nuova presentazione da zero. La presentazione creata ha una diapositiva vuota. |
| [Presentation](presentation#constructor_2)(Stream) | Questo costruttore è il meccanismo principale per leggere una presentazione esistente. |
| [Presentation](presentation#constructor_4)(string) | Questo costruttore ottiene il percorso del file di origine da cui vengono letti i contenuti della presentazione. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Questo costruttore è il meccanismo principale per leggere una presentazione esistente. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Questo costruttore ottiene il percorso del file di origine da cui vengono letti i contenuti della presentazione. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Restituisce tutte le parti di dati personalizzati nella presentazione. Solo lettura [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Restituisce la collezione di tutti i file audio incorporati nella presentazione. Solo lettura [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Restituisce la collezione degli autori dei commenti. Solo lettura [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. Per impostazione predefinita, l'ora di creazione di questo oggetto Presentation. Lettura/scrittura DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Restituisce i dati personalizzati della presentazione. Solo lettura [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Restituisce lo stile di testo predefinito per le forme. Solo lettura [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Restituisce la collezione di firme utilizzate per firmare la presentazione. Solo lettura [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Restituisce l'oggetto DocumentProperties che contiene le proprietà standard e personalizzate del documento. Solo lettura [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Rappresenta il numero della prima diapositiva nella presentazione |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Restituisce il gestore dei font. Solo lettura [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Restituisce il gestore corrente di HeaderFooter. Solo lettura [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Fornisce facile accesso a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (non nei master, layout, note). Solo lettura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Restituisce la collezione di tutte le immagini nella presentazione. Solo lettura [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Restituisce un elenco di tutte le diapositive layout definite nella presentazione. Solo lettura [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Restituisce il gestore del master per gli handout. Solo lettura [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Restituisce il gestore del master per le note. Solo lettura [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Restituisce un elenco di tutte le diapositive master definite nella presentazione. Solo lettura [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Restituisce il tema master. Solo lettura [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Restituisce l'oggetto dimensione della diapositiva note. Solo lettura [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Ottiene il gestore delle autorizzazioni per questa presentazione. Solo lettura [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Restituisce un elenco di tutte le sezioni di diapositive definite nella presentazione. Solo lettura [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Restituisce la collezione di etichette di sensibilità applicate al documento della presentazione. Solo lettura [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Restituisce un elenco di tutte le diapositive definite nella presentazione. Solo lettura [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Restituisce le impostazioni della presentazione della diapositiva. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Restituisce l'oggetto dimensione della diapositiva. Solo lettura [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Restituisce informazioni sul formato da cui è stata caricata la presentazione. Solo lettura [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Ottiene o imposta il progetto VBA con le macro della presentazione. Lettura/scrittura [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Restituisce la collezione di tutti i file video incorporati nella presentazione. Solo lettura [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Ottiene le proprietà di visualizzazione a livello di presentazione. Solo lettura [`IViewProperties`](../iviewproperties). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Rilascia tutte le risorse utilizzate da questo oggetto Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Restituisce oggetti Image per tutte le diapositive di una presentazione. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con la dimensione specificata. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con ridimensionamento personalizzato. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con la dimensione specificata. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con ridimensionamento personalizzato. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Restituisce una Slide, MasterSlide o LayoutSlide tramite Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Unisce le run con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili in tutte le diapositive. |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | Ricarica i dati per tutti i grafici nella presentazione dai loro workbook di origine. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano il markup XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Salva tutte le diapositive di una presentazione in un file con il formato specificato. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato mantenendo il numero di pagina. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato e con opzioni aggiuntive. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato mantenendo il numero di pagina. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina. |

### Esempi

Il seguente esempio mostra come creare una presentazione PowerPoint.

```csharp
[C#]
// Istanzia un oggetto Presentation che rappresenta un file di presentazione
using (Presentation presentation = new Presentation())
{
    // Ottieni la prima diapositiva
    ISlide slide = presentation.Slides[0];
    // Aggiungi una forma automatica di tipo linea
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Salva il file della presentazione.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Il seguente esempio mostra come aprire e salvare una presentazione.

```csharp
[C#]
// Carica qualsiasi file supportato in Presentation ad esempio ppt, pptx, odp ecc.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Salva il file della presentazione.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interfaccia [IPresentation](../ipresentation)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->