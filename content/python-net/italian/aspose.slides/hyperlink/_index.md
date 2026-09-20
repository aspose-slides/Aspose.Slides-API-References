---
title: Hyperlink class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/hyperlink/
---
## Hyperlink classe

Rappresenta un collegamento ipertestuale.

**Inheritance:**[`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/it/aspose.slides/pviobject)

Il tipo Hyperlink espone i seguenti membri:

## Costruttori

| Constructor | Description |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/it/aspose.slides/hyperlink/__init__/#str) | Crea un'istanza di un collegamento ipertestuale. |
| [`__init__(self, slide)`](/slides/python-net/it/aspose.slides/hyperlink/__init__/#islide) | Crea un'istanza di un collegamento ipertestuale che punta a una diapositiva specifica.<br/>            Nota: il collegamento ipertestuale creato deve essere assegnato a qualche oggetto della stessa presentazione, altrimenti il collegamento verrà salvato come NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/it/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Crea un'istanza di un collegamento ipertestuale usando un altro collegamento ipertestuale come sorgente, sovrascrivendo le proprietà secondarie. |

## Proprietà

| Property | Description |
| :- | :- |
| [`no_action`](/slides/python-net/it/aspose.slides/hyperlink/no_action/) | Restituisce un collegamento ipertestuale speciale "do nothing".<br/>            Sola lettura [`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/it/aspose.slides/hyperlink/media/) | Restituisce un collegamento ipertestuale speciale "play mediafile". Usato in AudioFrame e VideoFrame.<br/>            Sola lettura [`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/it/aspose.slides/hyperlink/next_slide/) | Restituisce un collegamento ipertestuale alla diapositiva successiva.<br/>            Sola lettura [`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/it/aspose.slides/hyperlink/previous_slide/) | Restituisce un collegamento ipertestuale alla diapositiva precedente.<br/>            Sola lettura [`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/it/aspose.slides/hyperlink/first_slide/) | Restituisce un collegamento ipertestuale alla prima diapositiva della presentazione.<br/>            Sola lettura [`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/it/aspose.slides/hyperlink/last_slide/) | Restituisce un collegamento ipertestuale all'ultima diapositiva della presentazione.<br/>            Sola lettura [`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/it/aspose.slides/hyperlink/last_vieved_slide/) | Restituisce un collegamento ipertestuale all'ultima diapositiva visualizzata.<br/>            Sola lettura [`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/it/aspose.slides/hyperlink/end_show/) | Restituisce un collegamento ipertestuale che termina la presentazione.<br/>            Sola lettura [`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/it/aspose.slides/hyperlink/action_type/) | Restituisce il tipo di azione del Hyperlink.<br/>            Sola lettura [`HyperlinkActionType`](/slides/python-net/it/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/it/aspose.slides/hyperlink/external_url/) | Specifica l'URL esterno.<br/>            Sola lettura **str**. |
| [`target_slide`](/slides/python-net/it/aspose.slides/hyperlink/target_slide/) | Se il Hyperlink punta a una diapositiva specifica, restituisce questa diapositiva.<br/>            Sola lettura [`ISlide`](/slides/python-net/it/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/it/aspose.slides/hyperlink/external_url_original/) | Rappresenta un collegamento ipertestuale impostato per questa porzione senza considerare il contenuto effettivo della porzione.<br/>            PowerPoint si comporta in modo specifico per i collegamenti e il loro testo corrispondente in una porzione. Consente di creare testo per il collegamento ipertestuale in<br/>            forma di URL valido, diverso dall'indirizzo reale del collegamento. In questo caso, quando visualizzi il collegamento nella finestra di modifica, verrà<br/>            modificato per corrispondere alla porzione di testo. Questa proprietà rappresenta il valore originale del collegamento ipertestuale. |
| [`target_frame`](/slides/python-net/it/aspose.slides/hyperlink/target_frame/) | Restituisce il frame all'interno del frameset HTML genitore per il target<br/>            del collegamento ipertestuale genitore quando esiste.<br/>            Lettura/scrittura **str**. |
| [`tooltip`](/slides/python-net/it/aspose.slides/hyperlink/tooltip/) | Restituisce la stringa che può essere mostrata in un'interfaccia utente<br/>            associata al collegamento ipertestuale genitore.<br/>            Lettura/scrittura **str**. |
| [`history`](/slides/python-net/it/aspose.slides/hyperlink/history/) | Determina se il target del collegamento ipertestuale genitore deve essere aggiunto<br/>            a una lista di collegamenti ipertestuali visualizzati quando viene invocato.<br/>            Lettura/scrittura **bool**. |
| [`highlight_click`](/slides/python-net/it/aspose.slides/hyperlink/highlight_click/) | Determina se il collegamento ipertestuale deve essere evidenziato al clic.<br/>            Lettura/scrittura **bool**. |
| [`stop_sound_on_click`](/slides/python-net/it/aspose.slides/hyperlink/stop_sound_on_click/) | Determina se il suono deve essere interrotto al clic sul collegamento ipertestuale.<br/>            Lettura/scrittura **bool**. |
| [`sound`](/slides/python-net/it/aspose.slides/hyperlink/sound/) | Rappresenta il suono in riproduzione del collegamento ipertestuale.<br/>            Lettura/scrittura [`IAudio`](/slides/python-net/it/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/it/aspose.slides/hyperlink/color_source/) | Rappresenta la fonte del colore del collegamento ipertestuale - stili o formato della porzione.<br/>            Lettura/scrittura [`HyperlinkColorSource`](/slides/python-net/it/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/it/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/hyperlink/presentation/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/it/aspose.slides/hyperlink/equals/#ihyperlink) | Determina se le due istanze di Hyperlink sono uguali. |


### Vedi anche
* classe [`Hyperlink`](/slides/python-net/it/aspose.slides/hyperlink)
* classe [`PVIObject`](/slides/python-net/it/aspose.slides/pviobject)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)