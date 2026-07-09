---
title: Presentation
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta una presentazione Microsoft PowerPoint.
type: docs
weight: 9590
url: /it/aspose.slides/presentation/
---
## Presentation classe

Rappresenta una presentazione Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Costruttori

| Name | Description |
| --- | --- |
| [Presentation](presentation#constructor)() | Questo costruttore crea una nuova presentazione da zero. La presentazione creata ha una diapositiva vuota. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Questo costruttore crea una nuova presentazione da zero. La presentazione creata ha una diapositiva vuota. |
| [Presentation](presentation#constructor_2)(Stream) | Questo costruttore è il meccanismo principale per leggere una presentazione esistente. |
| [Presentation](presentation#constructor_4)(string) | Questo costruttore ottiene un percorso file sorgente dal quale vengono letti i contenuti della presentazione. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Questo costruttore è il meccanismo principale per leggere una presentazione esistente. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Questo costruttore ottiene un percorso file sorgente dal quale vengono letti i contenuti della presentazione. |

## Proprietà

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Restituisce tutte le parti di dati personalizzati nella presentazione. Sola lettura [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Restituisce la raccolta di tutti i file audio incorporati nella presentazione. Sola lettura [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Restituisce la raccolta degli autori dei commenti. Sola lettura [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. Ora di creazione di questo oggetto Presentation per impostazione predefinita. Lettura/scrittura DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Restituisce i dati personalizzati della presentazione. Sola lettura [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Restituisce lo stile di testo predefinito per le forme. Sola lettura [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Restituisce la raccolta delle firme utilizzate per firmare la presentazione. Sola lettura [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Restituisce l'oggetto DocumentProperties che contiene le proprietà del documento standard e personalizzate. Sola lettura [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Rappresenta il numero della prima diapositiva nella presentazione |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Restituisce il gestore dei caratteri. Sola lettura [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Restituisce il gestore attuale HeaderFooter. Sola lettura [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Fornisce un facile accesso a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (non nelle master, layout, note). Sola lettura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Restituisce la raccolta di tutte le immagini nella presentazione. Sola lettura [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Restituisce un elenco di tutti i layout diapositive definiti nella presentazione. Sola lettura [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Restituisce il gestore del master handout. Sola lettura [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Restituisce il gestore del master note. Sola lettura [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Restituisce un elenco di tutti i master slide definiti nella presentazione. Sola lettura [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Restituisce il tema master. Sola lettura [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Restituisce l'oggetto dimensione diapositiva note. Sola lettura [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Ottiene il gestore dei permessi per questa presentazione. Sola lettura [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Restituisce un elenco di tutte le sezioni diapositive definite nella presentazione. Sola lettura [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Restituisce la raccolta delle etichette di sensibilità applicate al documento della presentazione. Sola lettura [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Restituisce un elenco di tutte le diapositive definite nella presentazione. Sola lettura [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Restituisce le impostazioni della presentazione. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Restituisce l'oggetto dimensione diapositiva. Sola lettura [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Restituisce informazioni sul formato da cui è stata caricata la presentazione. Sola lettura [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Ottiene o imposta il progetto VBA con le macro della presentazione. Lettura/scrittura [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Restituisce la raccolta di tutti i file video incorporati nella presentazione. Sola lettura [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Ottiene le proprietà di visualizzazione dell'intera presentazione. Sola lettura [`IViewProperties`](../iviewproperties). |

## Metodi

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Rilascia tutte le risorse utilizzate da questo oggetto Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Restituisce oggetti Image per tutte le diapositive di una presentazione. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con dimensioni specificate. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con scala personalizzata. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con dimensioni specificate. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con scala personalizzata. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Restituisce una Slide, MasterSlide o LayoutSlide per Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Unisce i run con lo stesso formato in tutti i paragrafi di tutte le forme accettabili in tutte le diapositive. |
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
// Istanziare un oggetto Presentation che rappresenta un file di presentazione
using (Presentation presentation = new Presentation())
{
    // Ottieni la prima diapositiva
    ISlide slide = presentation.Slides[0];
    // Aggiungi una forma automatica di tipo linea
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Salva il file di presentazione.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Il seguente esempio mostra come aprire e salvare una presentazione.

```csharp
[C#]
// Carica qualsiasi file supportato in Presentation, ad es. ppt, pptx, odp ecc.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Salva il file di presentazione.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interfaccia [IPresentation](../ipresentation)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->