---
title: NotesSlide class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/notesslide/
---
## NotesSlide classe

Rappresenta una diapositiva di note in una presentazione.

**Ereditarietà:**[`NotesSlide`](/slides/python-net/it/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)

Il tipo NotesSlide espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`shapes`](/slides/python-net/it/aspose.slides/notesslide/shapes/) | Restituisce le forme di una diapositiva.<br/>            Sola lettura [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/it/aspose.slides/notesslide/controls/) | Restituisce la collezione di controlli ActiveX su una diapositiva.<br/>            Sola lettura [`IControlCollection`](/slides/python-net/it/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/it/aspose.slides/notesslide/name/) | Restituisce o imposta il nome di una diapositiva.<br/>            Lettura/scrittura **str**. |
| [`slide_id`](/slides/python-net/it/aspose.slides/notesslide/slide_id/) | Restituisce l'ID di una diapositiva.<br/>            Sola lettura **int**. |
| [`custom_data`](/slides/python-net/it/aspose.slides/notesslide/custom_data/) | Restituisce i dati personalizzati della diapositiva.<br/>            Sola lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/it/aspose.slides/notesslide/timeline/) | Restituisce l'oggetto della timeline di animazione.<br/>            Sola lettura [`IAnimationTimeLine`](/slides/python-net/it/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/it/aspose.slides/notesslide/slide_show_transition/) | Restituisce l'oggetto Transition che contiene informazioni su<br/>            come la diapositiva specificata avanza durante una presentazione.<br/>            Sola lettura [`ISlideShowTransition`](/slides/python-net/it/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/it/aspose.slides/notesslide/background/) | Restituisce lo sfondo della diapositiva.<br/>            Sola lettura [`IBackground`](/slides/python-net/it/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/notesslide/hyperlink_queries/) | Fornisce un facile accesso ai collegamenti ipertestuali contenuti.<br/>            Sola lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/it/aspose.slides/notesslide/show_master_shapes/) | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno.<br/>            Lettura/scrittura **bool**. |
| [`presentation`](/slides/python-net/it/aspose.slides/notesslide/presentation/) | Restituisce l'interfaccia IPresentation.<br/>            Sola lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/it/aspose.slides/notesslide/header_footer_manager/) | Restituisce il gestore HeaderFooter della diapositiva di note.<br/>            Sola lettura [`INotesSlideHeaderFooterManager`](/slides/python-net/it/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/it/aspose.slides/notesslide/notes_text_frame/) | Restituisce un TextFrame con il testo delle note, se presente.<br/>            Sola lettura [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/it/aspose.slides/notesslide/theme_manager/) | Restituisce il gestore del tema sovrascrivente.<br/>            Sola lettura [`IOverrideThemeManager`](/slides/python-net/it/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/it/aspose.slides/notesslide/parent_slide/) | Restituisce la diapositiva genitore.<br/>            Sola lettura [`ISlide`](/slides/python-net/it/aspose.slides/islide). |
| [`slide`](/slides/python-net/it/aspose.slides/notesslide/slide/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Unisce le run con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/it/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Unisce le run con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili. |
| [`equals(self, slide)`](/slides/python-net/it/aspose.slides/notesslide/equals/#ibaseslide) | Determina se le due istanze di IBaseSlide sono uguali.<br/>            Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico.<br/>            Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e le altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad es. SlideId, né del contenuto dinamico, ad es. il valore della data corrente nel segnaposto Data. |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides/notesslide/create_theme_effective/#) | Restituisce un tema effettivo per questa diapositiva. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/it/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |

### Vedi anche
* classe [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)
* classe [`NotesSlide`](/slides/python-net/it/aspose.slides/notesslide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)