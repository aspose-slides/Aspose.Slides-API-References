---
title: MasterSlide class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/masterslide/
---
## MasterSlide classe

Rappresenta una diapositiva master in una presentazione.

**Inheritance:**[`MasterSlide`](/slides/python-net/it/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)

Il tipo MasterSlide espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`shapes`](/slides/python-net/it/aspose.slides/masterslide/shapes/) | Restituisce le forme di una diapositiva.<br/>            Sola lettura [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/it/aspose.slides/masterslide/controls/) | Restituisce la raccolta di controlli ActiveX su una diapositiva.<br/>            Sola lettura [`IControlCollection`](/slides/python-net/it/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/it/aspose.slides/masterslide/name/) | Restituisce o imposta il nome di una diapositiva master.<br/>            Lettura/scrittura **str**. |
| [`slide_id`](/slides/python-net/it/aspose.slides/masterslide/slide_id/) | Restituisce l'ID di una diapositiva.<br/>            Sola lettura **int**. |
| [`custom_data`](/slides/python-net/it/aspose.slides/masterslide/custom_data/) | Restituisce i dati personalizzati della diapositiva.<br/>            Sola lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/it/aspose.slides/masterslide/timeline/) | Restituisce l'oggetto timeline dell'animazione.<br/>            Sola lettura [`IAnimationTimeLine`](/slides/python-net/it/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/it/aspose.slides/masterslide/slide_show_transition/) | Restituisce l'oggetto Transition che contiene informazioni su<br/>            come la diapositiva specificata avanza durante una presentazione.<br/>            Sola lettura [`ISlideShowTransition`](/slides/python-net/it/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/it/aspose.slides/masterslide/background/) | Restituisce lo sfondo della diapositiva.<br/>            Sola lettura [`IBackground`](/slides/python-net/it/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/masterslide/hyperlink_queries/) | Fornisce un accesso semplice ai collegamenti ipertestuali contenuti.<br/>            Sola lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/it/aspose.slides/masterslide/show_master_shapes/) | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno.<br/>            Per la diapositiva master stessa questa proprietà restituisce sempre `false`.<br/>            Lettura/scrittura **bool**. |
| [`presentation`](/slides/python-net/it/aspose.slides/masterslide/presentation/) | Restituisce l'interfaccia IPresentation.<br/>            Sola lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/it/aspose.slides/masterslide/header_footer_manager/) | Restituisce il gestore HeaderFooter della diapositiva master.<br/>            Sola lettura [`IMasterSlideHeaderFooterManager`](/slides/python-net/it/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/it/aspose.slides/masterslide/title_style/) | Restituisce lo stile del testo del titolo.<br/>            Sola lettura [`ITextStyle`](/slides/python-net/it/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/it/aspose.slides/masterslide/body_style/) | Restituisce lo stile del testo del corpo.<br/>            Sola lettura [`ITextStyle`](/slides/python-net/it/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/it/aspose.slides/masterslide/other_style/) | Restituisce lo stile di un altro testo.<br/>            Sola lettura [`ITextStyle`](/slides/python-net/it/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/it/aspose.slides/masterslide/layout_slides/) | Restituisce la raccolta di layout diapositive figlio per questa diapositiva master.<br/>            Sola lettura [`IMasterLayoutSlideCollection`](/slides/python-net/it/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/it/aspose.slides/masterslide/preserve/) | Determina se la master corrispondente viene eliminata quando tutte le diapositive che seguono quella master vengono eliminate.<br/>            Nota: Aspose.Slides non rimuoverà mai alcuna master inutilizzata da solo; per rimuovere effettivamente le master inutilizzate chiamare **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            Lettura/scrittura **bool**. |
| [`has_depending_slides`](/slides/python-net/it/aspose.slides/masterslide/has_depending_slides/) | Restituisce true se esiste almeno una diapositiva che dipende da questa master slide.<br/>            Sola lettura **bool**. |
| [`theme_manager`](/slides/python-net/it/aspose.slides/masterslide/theme_manager/) | Restituisce il gestore del tema.<br/>            Sola lettura [`IMasterThemeManager`](/slides/python-net/it/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/it/aspose.slides/masterslide/drawing_guides/) | Restituisce una raccolta di guide di disegno per la diapositiva master.<br/>            Sola lettura [`IDrawingGuidesCollection`](/slides/python-net/it/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/it/aspose.slides/masterslide/slide/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Unisce le sequenze con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/it/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Unisce le sequenze con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili. |
| [`equals(self, slide)`](/slides/python-net/it/aspose.slides/masterslide/equals/#ibaseslide) | Determina se le due istanze di IBaseSlide sono uguali.<br/>            Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico.<br/>            Due diapositive sono uguali se tutte le forme, stili, testi, animazioni e altre impostazioni, ecc., sono uguali. Il confronto non considera i valori degli identificatori unici, ad esempio SlideId, né il contenuto dinamico, ad esempio il valore della data corrente nel segnaposto Data. |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides/masterslide/create_theme_effective/#) | Restituisce un tema effettivo per questa diapositiva. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/it/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/it/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Crea una nuova diapositiva master basata su quella corrente, applicando un tema esterno ad essa<br/>            e applica la master slide creata a tutte le diapositive dipendenti. |
| [`get_depending_slides(self)`](/slides/python-net/it/aspose.slides/masterslide/get_depending_slides/#) | Restituisce un array con tutte le diapositive che dipendono da questa master slide. |


### Vedi anche
* classe [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)
* classe [`MasterSlide`](/slides/python-net/it/aspose.slides/masterslide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)