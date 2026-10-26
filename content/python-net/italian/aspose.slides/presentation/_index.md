---
title: Presentation class
second_title: Aspose.Slides per Python tramite .NET API Reference
description: 
type: docs
url: /it/aspose.slides/presentation/
---
## Classe Presentation

Rappresenta una presentazione Microsoft PowerPoint.

Il tipo Presentation espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides/presentation/__init__/#) | Questo costruttore crea una nuova presentazione da zero.<br/>            La presentazione creata ha una diapositiva vuota. |
| [`__init__(self, load_options)`](/slides/python-net/it/aspose.slides/presentation/__init__/#loadoptions) | Questo costruttore crea una nuova presentazione da zero.<br/>            La presentazione creata ha una diapositiva vuota. |
| [`__init__(self, stream)`](/slides/python-net/it/aspose.slides/presentation/__init__/#iorawiobase) | Questo costruttore è il meccanismo principale per leggere una Presentation esistente. |
| [`__init__(self, stream, load_options)`](/slides/python-net/it/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Questo costruttore è il meccanismo principale per leggere una Presentation esistente. |
| [`__init__(self, file)`](/slides/python-net/it/aspose.slides/presentation/__init__/#str) | Questo costruttore ottiene un percorso file sorgente da cui<br/>             il contenuto della Presentation viene letto. |
| [`__init__(self, file, load_options)`](/slides/python-net/it/aspose.slides/presentation/__init__/#str-loadoptions) | Questo costruttore ottiene un percorso file sorgente da cui<br/>            il contenuto della Presentation viene letto. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`current_date_time`](/slides/python-net/it/aspose.slides/presentation/current_date_time/) | Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime.<br/>            L'ora di creazione di questo oggetto Presentation per impostazione predefinita.<br/>            Lettura/Scrittura **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/it/aspose.slides/presentation/header_footer_manager/) | Restituisce il gestore HeaderFooter attuale.<br/>            Sola lettura [`IPresentationHeaderFooterManager`](/slides/python-net/it/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/it/aspose.slides/presentation/protection_manager/) | Ottiene il gestore delle autorizzazioni per questa presentazione.<br/>            Sola lettura [`IProtectionManager`](/slides/python-net/it/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/it/aspose.slides/presentation/slides/) | Restituisce un elenco di tutte le diapositive definite nella presentazione.<br/it/>            Sola lettura [`ISlideCollection`](/slides/python-net/it/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/it/aspose.slides/presentation/sections/) | Restituisce un elenco di tutte le sezioni diapositive definite nella presentazione.<br/>            Sola lettura [`ISectionCollection`](/slides/python-net/it/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/it/aspose.slides/presentation/slide_size/) | Restituisce l'oggetto dimensione diapositiva.<br/>            Sola lettura [`ISlideSize`](/slides/python-net/it/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/it/aspose.slides/presentation/notes_size/) | Restituisce l'oggetto dimensione diapositiva note.<br/>            Sola lettura [`INotesSize`](/slides/python-net/it/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/it/aspose.slides/presentation/layout_slides/) | Restituisce un elenco di tutte le diapositive layout definite nella presentazione.<br/>            Sola lettura [`IGlobalLayoutSlideCollection`](/slides/python-net/it/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/it/aspose.slides/presentation/masters/) | Restituisce un elenco di tutte le diapositive master definite nella presentazione.<br/>            Sola lettura [`IMasterSlideCollection`](/slides/python-net/it/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/it/aspose.slides/presentation/master_notes_slide_manager/) | Restituisce il gestore master note.<br/>            Sola lettura [`IMasterNotesSlideManager`](/slides/python-net/it/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/it/aspose.slides/presentation/master_handout_slide_manager/) | Restituisce il gestore master dispense.<br/>            Sola lettura [`IMasterHandoutSlideManager`](/slides/python-net/it/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/it/aspose.slides/presentation/fonts_manager/) | Restituisce il gestore dei caratteri.<br/>            Sola lettura [`IFontsManager`](/slides/python-net/it/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/it/aspose.slides/presentation/default_text_style/) | Restituisce lo stile di testo predefinito per le forme.<br/>            Sola lettura [`ITextStyle`](/slides/python-net/it/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/it/aspose.slides/presentation/comment_authors/) | Restituisce la raccolta degli autori dei commenti.<br/>            Sola lettura [`ICommentAuthorCollection`](/slides/python-net/it/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/it/aspose.slides/presentation/document_properties/) | Restituisce l'oggetto DocumentProperties che contiene proprietà documento standard e personalizzate.<br/>            Sola lettura [`IDocumentProperties`](/slides/python-net/it/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/it/aspose.slides/presentation/images/) | Restituisce la raccolta di tutte le immagini nella presentazione.<br/>            Sola lettura [`IImageCollection`](/slides/python-net/it/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/it/aspose.slides/presentation/audios/) | Restituisce la raccolta di tutti i file audio incorporati nella presentazione.<br/>            Sola lettura [`IAudioCollection`](/slides/python-net/it/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/it/aspose.slides/presentation/videos/) | Restituisce la raccolta di tutti i file video incorporati nella presentazione.<br/>            Sola lettura [`IVideoCollection`](/slides/python-net/it/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/it/aspose.slides/presentation/slide_show_settings/) | Restituisce le impostazioni della presentazione a schermo. |
| [`digital_signatures`](/slides/python-net/it/aspose.slides/presentation/digital_signatures/) | Restituisce la raccolta di firme utilizzate per firmare la presentazione.<br/>            Sola lettura [`IDigitalSignatureCollection`](/slides/python-net/it/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/it/aspose.slides/presentation/custom_data/) | Restituisce i dati personalizzati della presentazione.<br/>            Sola lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/it/aspose.slides/presentation/all_custom_xml_parts/) | Restituisce tutte le parti dei dati personalizzati nella presentazione.<br/>            Sola lettura [`ICustomXmlPart`](/slides/python-net/it/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/it/aspose.slides/presentation/vba_project/) | Ottiene o imposta il progetto VBA con le macro della presentazione.<br/>            Lettura/Scrittura [`IVbaProject`](/slides/python-net/it/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/presentation/hyperlink_queries/) | Fornisce un facile accesso a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (non in quelle master, layout, note).<br/>            Sola lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/it/aspose.slides/presentation/view_properties/) | Ottiene le proprietà di visualizzazione a livello di presentazione.<br/>            Sola lettura [`IViewProperties`](/slides/python-net/it/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/it/aspose.slides/presentation/first_slide_number/) | Rappresenta il numero della prima diapositiva nella presentazione |
| [`sensitivity_labels`](/slides/python-net/it/aspose.slides/presentation/sensitivity_labels/) | Restituisce la raccolta di etichette di sensibilità applicate al documento della presentazione.<br/>            Sola lettura [`ISensitivityLabelCollection`](/slides/python-net/it/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/it/aspose.slides/presentation/source_format/) | Restituisce informazioni sul formato da cui la presentazione è stata caricata.<br/>            Sola lettura [`SourceFormat`](/slides/python-net/it/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/it/aspose.slides/presentation/master_theme/) | Restituisce il tema master.<br/>            Sola lettura [`IMasterTheme`](/slides/python-net/it/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/it/aspose.slides/presentation/presentation/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/it/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Salva tutte le diapositive di una presentazione in un file con il formato specificato. |
| [`save(self, stream, format)`](/slides/python-net/it/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato. |
| [`save(self, fname, format, options)`](/slides/python-net/it/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/it/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato e con opzioni aggiuntive. |
| [`save(self, options)`](/slides/python-net/it/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano il markup XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/it/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/it/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina. |
| [`save(self, stream, slides, format)`](/slides/python-net/it/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato mantenendo il numero di pagina. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/it/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato mantenendo il numero di pagina. |
| [`get_images(self, options)`](/slides/python-net/it/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Restituisce oggetti Image per tutte le diapositive di una presentazione. |
| [`get_images(self, options, slides)`](/slides/python-net/it/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con scala personalizzata. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con scala personalizzata. |
| [`get_images(self, options, image_size)`](/slides/python-net/it/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con dimensione specificata. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/it/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con dimensione specificata. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/it/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/it/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [`get_slide_by_id(self, id)`](/slides/python-net/it/aspose.slides/presentation/get_slide_by_id/#int) | Restituisce una Slide, MasterSlide o LayoutSlide per Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/presentation/join_portions_with_same_formatting/#) | Unisce le run con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili in tutte le diapositive. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/it/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Evidenzia tutte le occorrenze dell'espressione regolare con il colore specificato. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/it/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/it/aspose.slides/presentation/replace_regex/#str-str) | Sostituisce tutte le occorrenze dell'espressione regolare con la stringa specificata. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)