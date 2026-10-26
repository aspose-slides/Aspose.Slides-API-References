---
title: Slide class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/slide/
---
## classe Slide

Rappresenta una diapositiva in una presentazione.

**Eredità:**[`Slide`](/slides/python-net/it/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)

Il tipo Slide espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`shapes`](/slides/python-net/it/aspose.slides/slide/shapes/) | Restituisce le forme di una diapositiva.<br/>            Solo lettura [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/it/aspose.slides/slide/controls/) | Restituisce la raccolta di controlli ActiveX su una diapositiva.<br/>            Solo lettura [`IControlCollection`](/slides/python-net/it/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/it/aspose.slides/slide/name/) | Restituisce o imposta il nome di una diapositiva.<br/>            Lettura/scrittura **str**. |
| [`slide_id`](/slides/python-net/it/aspose.slides/slide/slide_id/) | Restituisce l'ID di una diapositiva.<br/>            Solo lettura **int**. |
| [`custom_data`](/slides/python-net/it/aspose.slides/slide/custom_data/) | Restituisce i dati personalizzati della diapositiva.<br/>            Solo lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/it/aspose.slides/slide/timeline/) | Restituisce l'oggetto timeline dell'animazione.<br/>            Solo lettura [`IAnimationTimeLine`](/slides/python-net/it/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/it/aspose.slides/slide/slide_show_transition/) | Restituisce l'oggetto Transition che contiene informazioni su<br/>            come la diapositiva specificata avanza durante una presentazione.<br/>            Solo lettura [`ISlideShowTransition`](/slides/python-net/it/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/it/aspose.slides/slide/background/) | Restituisce lo sfondo della diapositiva.<br/>            Solo lettura [`IBackground`](/slides/python-net/it/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/slide/hyperlink_queries/) | Fornisce un facile accesso ai collegamenti ipertestuali contenuti.<br/>            Solo lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/it/aspose.slides/slide/show_master_shapes/) | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno.<br/>            Lettura/scrittura **bool**. |
| [`presentation`](/slides/python-net/it/aspose.slides/slide/presentation/) | Restituisce l'interfaccia IPresentation.<br/>            Solo lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/it/aspose.slides/slide/header_footer_manager/) | Restituisce il gestore HeaderFooter della diapositiva.<br/>            Solo lettura [`ISlideHeaderFooterManager`](/slides/python-net/it/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/it/aspose.slides/slide/theme_manager/) | Restituisce il gestore del tema sovrascritto.<br/>            Solo lettura [`IOverrideThemeManager`](/slides/python-net/it/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/it/aspose.slides/slide/slide_number/) | Restituisce il numero della diapositiva.<br/>            L'indice della diapositiva nella raccolta [`Presentation.slides`](/slides/python-net/it/aspose.slides/presentation/slides) è sempre uguale a SlideNumber - Presentation.FirstSlideNumber.<br/>            Lettura/scrittura **int**. |
| [`hidden`](/slides/python-net/it/aspose.slides/slide/hidden/) | Determina se la diapositiva specificata è nascosta durante una presentazione.<br/>            Lettura/scrittura **bool**. |
| [`layout_slide`](/slides/python-net/it/aspose.slides/slide/layout_slide/) | Restituisce o imposta la diapositiva layout per la diapositiva corrente.<br/>            Lettura/scrittura [`ILayoutSlide`](/slides/python-net/it/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/it/aspose.slides/slide/notes_slide_manager/) | Consente di accedere alla diapositiva delle note, aggiungerla e rimuoverla.<br/>            Solo lettura [`INotesSlideManager`](/slides/python-net/it/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/it/aspose.slides/slide/slide/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/slide/join_portions_with_same_formatting/#) | Unisce le esecuzioni con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/it/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Unisce le esecuzioni con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/slide/get_image/#float-float) | Restituisce un oggetto Thumbnail Image con scala personalizzata. |
| [`get_image(self)`](/slides/python-net/it/aspose.slides/slide/get_image/#) | Restituisce un oggetto Thumbnail Image (20% della dimensione reale). |
| [`get_image(self, image_size)`](/slides/python-net/it/aspose.slides/slide/get_image/#asposeslidessize) | Restituisce un oggetto Thumbnail Image con dimensione specificata. |
| [`get_image(self, options)`](/slides/python-net/it/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Restituisce un oggetto Thumbnail tiff con parametri specificati. |
| [`get_image(self, options)`](/slides/python-net/it/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Restituisce un oggetto Thumbnail Image. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/it/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Restituisce un oggetto Thumbnail Image con scala personalizzata. |
| [`get_image(self, options, image_size)`](/slides/python-net/it/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Restituisce un oggetto Thumbnail Image con dimensione specificata. |
| [`write_as_svg(self, stream)`](/slides/python-net/it/aspose.slides/slide/write_as_svg/#iorawiobase) | Salva il contenuto della diapositiva come file SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/it/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Salva il contenuto della diapositiva come file SVG. |
| [`equals(self, slide)`](/slides/python-net/it/aspose.slides/slide/equals/#ibaseslide) | Determina se le due istanze IBaseSlide sono uguali.<br/>            Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico.<br/>            Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e altre impostazioni, ecc., sono uguali. Il confronto non considera i valori degli identificatori unici, ad es. SlideId, né i contenuti dinamici, ad es. il valore corrente della data nel segnaposto Data. |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides/slide/create_theme_effective/#) | Restituisce un tema efficace per questa diapositiva. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/it/aspose.slides/slide/find_shape_by_alt_text/#str) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |
| [`write_as_emf(self, stream)`](/slides/python-net/it/aspose.slides/slide/write_as_emf/#iorawiobase) | Salva il contenuto della diapositiva come file EMF. |
| [`remove(self)`](/slides/python-net/it/aspose.slides/slide/remove/#) | Rimuove la diapositiva dalla presentazione. |
| [`reset(self)`](/slides/python-net/it/aspose.slides/slide/reset/#) | Ripristina posizione, dimensione e formattazione di ogni forma che ha un prototipo su LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/it/aspose.slides/slide/get_slide_comments/#icommentauthor) | Restituisce tutti i commenti della diapositiva aggiunti da uno specifico autore. |


### Vedi anche
* classe [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)
* classe [`Slide`](/slides/python-net/it/aspose.slides/slide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)