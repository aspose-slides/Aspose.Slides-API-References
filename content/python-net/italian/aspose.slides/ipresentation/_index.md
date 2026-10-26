---
title: IPresentation class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ipresentation/
---
## IPresentation classe

Documento di presentazione

Il tipo IPresentation espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`current_date_time`](/slides/python-net/it/aspose.slides/ipresentation/current_date_time/) | Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime.<br/>            Ora di creazione di questo oggetto Presentation per impostazione predefinita.<br/>            Lettura/scrittura **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/it/aspose.slides/ipresentation/header_footer_manager/) | Restituisce il gestore HeaderFooter della presentazione.<br/>            Sola lettura [`IPresentationHeaderFooterManager`](/slides/python-net/it/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/it/aspose.slides/ipresentation/protection_manager/) | Ottiene il gestore delle autorizzazioni per questa presentazione.<br/>            Sola lettura [`IProtectionManager`](/slides/python-net/it/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/it/aspose.slides/ipresentation/slides/) | Restituisce un elenco di tutte le diapositive definite nella presentazione.<br/it/>            Sola lettura [`ISlideCollection`](/slides/python-net/it/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/it/aspose.slides/ipresentation/sections/) | Restituisce un elenco di tutte le sezioni diapositive definite nella presentazione.<br/>            Sola lettura [`ISectionCollection`](/slides/python-net/it/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/it/aspose.slides/ipresentation/slide_size/) | Restituisce l'oggetto dimensione diapositiva.<br/>            Sola lettura [`ISlideSize`](/slides/python-net/it/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/it/aspose.slides/ipresentation/notes_size/) | Restituisce l'oggetto dimensione diapositiva note.<br/>            Sola lettura [`INotesSize`](/slides/python-net/it/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/it/aspose.slides/ipresentation/layout_slides/) | Restituisce un elenco di tutte le diapositive layout definite nella presentazione.<br/>            Sola lettura [`IGlobalLayoutSlideCollection`](/slides/python-net/it/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/it/aspose.slides/ipresentation/masters/) | Restituisce un elenco di tutte le diapositive master definite nella presentazione.<br/>            Sola lettura [`IMasterSlideCollection`](/slides/python-net/it/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/it/aspose.slides/ipresentation/master_notes_slide_manager/) | Restituisce il gestore del master delle note.<br/>            Sola lettura [`IMasterNotesSlideManager`](/slides/python-net/it/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/it/aspose.slides/ipresentation/master_handout_slide_manager/) | Restituisce il gestore del master del fascicolo.<br/>            Sola lettura [`IMasterHandoutSlideManager`](/slides/python-net/it/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/it/aspose.slides/ipresentation/fonts_manager/) | Restituisce il gestore dei caratteri.<br/>            Sola lettura [`IFontsManager`](/slides/python-net/it/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/it/aspose.slides/ipresentation/default_text_style/) | Restituisce lo stile di testo predefinito per le forme.<br/>            Sola lettura [`ITextStyle`](/slides/python-net/it/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/it/aspose.slides/ipresentation/comment_authors/) | Restituisce la collezione degli autori dei commenti.<br/>            Sola lettura [`ICommentAuthorCollection`](/slides/python-net/it/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/it/aspose.slides/ipresentation/document_properties/) | Restituisce l'oggetto DocumentProperties che contiene le proprietà standard e personalizzate del documento.<br/>            Sola lettura [`IDocumentProperties`](/slides/python-net/it/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/it/aspose.slides/ipresentation/images/) | Restituisce la collezione di tutte le immagini nella presentazione.<br/>            Sola lettura [`IImageCollection`](/slides/python-net/it/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/it/aspose.slides/ipresentation/audios/) | Restituisce la collezione di tutti i file audio incorporati nella presentazione.<br/>            Sola lettura [`IAudioCollection`](/slides/python-net/it/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/it/aspose.slides/ipresentation/videos/) | Restituisce la collezione di tutti i file video incorporati nella presentazione.<br/>            Sola lettura [`IVideoCollection`](/slides/python-net/it/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/it/aspose.slides/ipresentation/custom_data/) | Restituisce i dati personalizzati della presentazione.<br/>            Sola lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/it/aspose.slides/ipresentation/vba_project/) | Ottiene il progetto VBA con le macro della presentazione.<br/>            Lettura/scrittura [`IVbaProject`](/slides/python-net/it/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/it/aspose.slides/ipresentation/source_format/) | Restituisce informazioni sul formato da cui è stata caricata la presentazione.<br/>            Sola lettura [`IPresentation.source_format`](/slides/python-net/it/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/it/aspose.slides/ipresentation/master_theme/) | Restituisce il tema master della presentazione.<br/>            Sola lettura [`IMasterTheme`](/slides/python-net/it/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/ipresentation/hyperlink_queries/) | Fornisce un facile accesso a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (esclusi master, layout, diapositive note).<br/>            Sola lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/it/aspose.slides/ipresentation/view_properties/) | Ottiene le proprietà di visualizzazione a livello di presentazione.<br/>            Sola lettura [`IViewProperties`](/slides/python-net/it/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/it/aspose.slides/ipresentation/first_slide_number/) | Rappresenta il numero della prima diapositiva nella presentazione.<br/>            Lettura/scrittura **int**. |
| [`all_custom_xml_parts`](/slides/python-net/it/aspose.slides/ipresentation/all_custom_xml_parts/) | Restituisce tutte le parti di dati personalizzate nella presentazione.<br/>            Sola lettura [`ICustomXmlPart`](/slides/python-net/it/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/it/aspose.slides/ipresentation/digital_signatures/) | Restituisce la collezione delle firme utilizzate per firmare la presentazione.<br/>            Sola lettura [`IDigitalSignatureCollection`](/slides/python-net/it/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/it/aspose.slides/ipresentation/sensitivity_labels/) | Restituisce la collezione delle etichette di sensibilità applicate al documento della presentazione.<br/>            Sola lettura [`ISensitivityLabelCollection`](/slides/python-net/it/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/it/aspose.slides/ipresentation/presentation/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/it/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | Salva tutte le diapositive di una presentazione in un file con il formato specificato. |
| [`save(self, stream, format)`](/slides/python-net/it/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato. |
| [`save(self, fname, format, options)`](/slides/python-net/it/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive. |
| [`save(self, stream, format, options)`](/slides/python-net/it/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato e con opzioni aggiuntive. |
| [`save(self, fname, slides, format)`](/slides/python-net/it/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | Salva le diapositive specificate di una presentazione in un file con il formato specificato. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/it/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Salva le diapositive specificate di una presentazione in un file con il formato specificato. |
| [`save(self, stream, slides, format)`](/slides/python-net/it/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/it/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato. |
| [`save(self, options)`](/slides/python-net/it/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano il markup XAML. |
| [`get_images(self, options)`](/slides/python-net/it/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione. |
| [`get_images(self, options, slides)`](/slides/python-net/it/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | Restituisce oggetti Thumbnail Bitmap per le diapositive specificate di una presentazione. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con scala personalizzata. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con scala personalizzata. |
| [`get_images(self, options, image_size)`](/slides/python-net/it/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con dimensione specificata. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/it/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con dimensione specificata. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/it/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/it/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [`get_slide_by_id(self, id)`](/slides/python-net/it/aspose.slides/ipresentation/get_slide_by_id/#int) | Restituisce una Slide, MasterSlide o LayoutSlide per Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | Unisce le sequenze con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili in tutte le diapositive. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/it/aspose.slides/ipresentation/highlight_regex/#str-asposeslidescolor) | Evidenzia tutte le occorrenze dell'espressione regolare con il colore specificato. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/it/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/it/aspose.slides/ipresentation/replace_regex/#str-str) | Sostituisce tutte le occorrenze dell'espressione regolare con la stringa specificata. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)