---
title: MasterHandoutSlide class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide classe

Rappresenta la diapositiva master per i handout.

**Eredità:**[`MasterHandoutSlide`](/slides/python-net/it/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)

Il tipo MasterHandoutSlide espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`shapes`](/slides/python-net/it/aspose.slides/masterhandoutslide/shapes/) | Restituisce le forme di una diapositiva.<br/>            Solo lettura [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/it/aspose.slides/masterhandoutslide/controls/) | Restituisce la raccolta di controlli ActiveX su una diapositiva.<br/>            Solo lettura [`IControlCollection`](/slides/python-net/it/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/it/aspose.slides/masterhandoutslide/name/) | Restituisce o imposta il nome di una diapositiva.<br/>            Lettura/scrittura **str**. |
| [`slide_id`](/slides/python-net/it/aspose.slides/masterhandoutslide/slide_id/) | Restituisce l'ID di una diapositiva.<br/>            Solo lettura **int**. |
| [`custom_data`](/slides/python-net/it/aspose.slides/masterhandoutslide/custom_data/) | Restituisce i dati personalizzati della diapositiva.<br/>            Solo lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/it/aspose.slides/masterhandoutslide/timeline/) | Restituisce l'oggetto della timeline di animazione.<br/>            Solo lettura [`IAnimationTimeLine`](/slides/python-net/it/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/it/aspose.slides/masterhandoutslide/slide_show_transition/) | Restituisce l'oggetto Transition che contiene informazioni su<br/>            come la diapositiva specificata avanza durante una presentazione.<br/>            Solo lettura [`ISlideShowTransition`](/slides/python-net/it/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/it/aspose.slides/masterhandoutslide/background/) | Restituisce lo sfondo della diapositiva.<br/>            Solo lettura [`IBackground`](/slides/python-net/it/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/masterhandoutslide/hyperlink_queries/) | Fornisce un facile accesso ai collegamenti ipertestuali contenuti.<br/>            Solo lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/it/aspose.slides/masterhandoutslide/show_master_shapes/) | Specifica se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno.<br/>            Per la diapositiva master stessa questa proprietà restituisce sempre `false`.<br/>            Lettura/scrittura **bool**. |
| [`presentation`](/slides/python-net/it/aspose.slides/masterhandoutslide/presentation/) | Restituisce l'interfaccia IPresentation.<br/>            Solo lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/it/aspose.slides/masterhandoutslide/header_footer_manager/) | Restituisce il gestore HeaderFooter della diapositiva master handout.<br/>            Solo lettura [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/it/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/it/aspose.slides/masterhandoutslide/theme_manager/) | Restituisce il gestore dei temi.<br/>            Solo lettura [`IMasterThemeManager`](/slides/python-net/it/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/it/aspose.slides/masterhandoutslide/drawing_guides/) | Restituisce una raccolta di guide di disegno per la diapositiva master handout.<br/>            Solo lettura [`IDrawingGuidesCollection`](/slides/python-net/it/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/it/aspose.slides/masterhandoutslide/slide/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Unisce le sequenze con la stessa formattazione in tutti i paragrafi di tutte le forme ammissibili. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/it/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Unisce le sequenze con la stessa formattazione in tutti i paragrafi in tutte le forme ammissibili. |
| [`equals(self, slide)`](/slides/python-net/it/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Determina se le due istanze di IBaseSlide sono uguali.<br/>            Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico.<br/>            Due diapositive sono uguali se tutte le forme, gli stili, i testi, l'animazione e altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad es. SlideId, né del contenuto dinamico, ad es. il valore della data corrente nel segnaposto Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides/masterhandoutslide/create_theme_effective/#) | Restituisce un tema efficace per questa diapositiva. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/it/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |

### Vedi anche
* classe [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)
* classe [`MasterHandoutSlide`](/slides/python-net/it/aspose.slides/masterhandoutslide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)