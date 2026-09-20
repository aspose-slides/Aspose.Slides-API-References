---
title: MasterNotesSlide class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/masternotesslide/
---
## MasterNotesSlide classe

Represents master slide for notes.

**Inheritance:**[`MasterNotesSlide`](/slides/python-net/it/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)

The MasterNotesSlide type exposes the following members:

## Proprietà

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/it/aspose.slides/masternotesslide/shapes/) | Restituisce le forme di una diapositiva.<br/>            Solo lettura [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/it/aspose.slides/masternotesslide/controls/) | Restituisce la collezione di controlli ActiveX su una diapositiva.<br/>            Solo lettura [`IControlCollection`](/slides/python-net/it/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/it/aspose.slides/masternotesslide/name/) | Restituisce o imposta il nome di una diapositiva.<br/>            Lettura/scrittura **str**. |
| [`slide_id`](/slides/python-net/it/aspose.slides/masternotesslide/slide_id/) | Restituisce l'ID di una diapositiva.<br/>            Solo lettura **int**. |
| [`custom_data`](/slides/python-net/it/aspose.slides/masternotesslide/custom_data/) | Restituisce i dati personalizzati della diapositiva.<br/>            Solo lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/it/aspose.slides/masternotesslide/timeline/) | Restituisce l'oggetto della timeline dell'animazione.<br/>            Solo lettura [`IAnimationTimeLine`](/slides/python-net/it/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/it/aspose.slides/masternotesslide/slide_show_transition/) | Restituisce l'oggetto Transition che contiene informazioni su<br/>            come la diapositiva specificata avanza durante una presentazione.<br/>            Solo lettura [`ISlideShowTransition`](/slides/python-net/it/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/it/aspose.slides/masternotesslide/background/) | Restituisce lo sfondo della diapositiva.<br/>            Solo lettura [`IBackground`](/slides/python-net/it/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/masternotesslide/hyperlink_queries/) | Fornisce un facile accesso ai collegamenti ipertestuali contenuti.<br/>            Solo lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/it/aspose.slides/masternotesslide/show_master_shapes/) | Specifica se le forme sulla diapositiva master debbano essere mostrate sulle diapositive o meno.<br/>            Per la diapositiva master stessa questa proprietà restituisce sempre `false`.<br/>            Lettura/scrittura **bool**. |
| [`presentation`](/slides/python-net/it/aspose.slides/masternotesslide/presentation/) | Restituisce l'interfaccia IPresentation.<br/>            Solo lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/it/aspose.slides/masternotesslide/header_footer_manager/) | Restituisce il gestore HeaderFooter della diapositiva note master.<br/>            Solo lettura [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/it/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/it/aspose.slides/masternotesslide/theme_manager/) | Restituisce il gestore del tema.<br/>            Solo lettura [`IMasterThemeManager`](/slides/python-net/it/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/it/aspose.slides/masternotesslide/notes_style/) | Restituisce lo stile di un testo delle note.<br/>            Solo lettura [`ITextStyle`](/slides/python-net/it/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/it/aspose.slides/masternotesslide/drawing_guides/) | Restituisce una collezione di guide di disegno per la diapositiva note master.<br/>            Solo lettura [`IDrawingGuidesCollection`](/slides/python-net/it/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/it/aspose.slides/masternotesslide/slide/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Unisce le run con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/it/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Unisce le run con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili. |
| [`equals(self, slide)`](/slides/python-net/it/aspose.slides/masternotesslide/equals/#ibaseslide) | Determina se le due istanze di IBaseSlide sono uguali.<br/>            Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico.<br/>            Due diapositive sono uguali se tutte le forme, gli stili, i testi, l'animazione e le altre impostazioni, ecc. sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad esempio SlideId, e del contenuto dinamico, ad esempio il valore della data corrente nel Segnaposto Data. |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides/masternotesslide/create_theme_effective/#) | Restituisce un tema efficace per questa diapositiva. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/it/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |


### Vedi anche
* classe [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)
* classe [`MasterNotesSlide`](/slides/python-net/it/aspose.slides/masternotesslide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)