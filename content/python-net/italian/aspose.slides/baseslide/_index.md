---
title: BaseSlide class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/baseslide/
---
## BaseSlide classe

Rappresenta i dati comuni per tutti i tipi di diapositiva.

Il tipo BaseSlide espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`shapes`](/slides/python-net/it/aspose.slides/baseslide/shapes/) | Restituisce le forme di una diapositiva.<br/>            Sola lettura [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/it/aspose.slides/baseslide/controls/) | Restituisce la raccolta di controlli ActiveX su una diapositiva.<br/>            Sola lettura [`IControlCollection`](/slides/python-net/it/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/it/aspose.slides/baseslide/name/) | Restituisce o imposta il nome di una diapositiva.<br/>            Lettura/scrittura **str**. |
| [`slide_id`](/slides/python-net/it/aspose.slides/baseslide/slide_id/) | Restituisce l'ID di una diapositiva.<br/>            Sola lettura **int**. |
| [`custom_data`](/slides/python-net/it/aspose.slides/baseslide/custom_data/) | Restituisce i dati personalizzati della diapositiva.<br/>            Sola lettura [`ICustomData`](/slides/python-net/it/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/it/aspose.slides/baseslide/timeline/) | Restituisce l'oggetto della timeline di animazione.<br/>            Sola lettura [`IAnimationTimeLine`](/slides/python-net/it/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/it/aspose.slides/baseslide/slide_show_transition/) | Restituisce l'oggetto Transition che contiene informazioni su<br/>            come la diapositiva specificata avanza durante una presentazione.<br/>            Sola lettura [`ISlideShowTransition`](/slides/python-net/it/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/it/aspose.slides/baseslide/background/) | Restituisce lo sfondo della diapositiva.<br/>            Sola lettura [`IBackground`](/slides/python-net/it/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/baseslide/hyperlink_queries/) | Fornisce un accesso facile ai collegamenti ipertestuali contenuti.<br/>            Sola lettura [`IHyperlinkQueries`](/slides/python-net/it/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/it/aspose.slides/baseslide/show_master_shapes/) | Specifica se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno.<br/>            Per la diapositiva master stessa questa proprietà restituisce sempre `false`.<br/>            Lettura/scrittura **bool**. |
| [`presentation`](/slides/python-net/it/aspose.slides/baseslide/presentation/) | Restituisce l'interfaccia IPresentation.<br/>            Sola lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/it/aspose.slides/baseslide/slide/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Unisce le sequenze con lo stesso formato in tutti i paragrafi di tutte le forme ammissibili. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/it/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Unisce le sequenze con lo stesso formato in tutti i paragrafi di tutte le forme ammissibili. |
| [`equals(self, slide)`](/slides/python-net/it/aspose.slides/baseslide/equals/#ibaseslide) | Determina se le due istanze IBaseSlide sono uguali.<br/>            Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico.<br/>            Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori di identificatore univoco, ad esempio SlideId, e del contenuto dinamico, ad esempio il valore della data corrente nel segnaposto Data. |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides/baseslide/create_theme_effective/#) | Restituisce un tema efficace per questa diapositiva. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/it/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)