---
title: IHyperlink class
second_title: Aspose.Slides per Python tramite .NET - Riferimento API
description: 
type: docs
url: /it/aspose.slides/ihyperlink/
---
## IHyperlink classe

Rappresenta un collegamento ipertestuale.

Il tipo IHyperlink espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`action_type`](/slides/python-net/it/aspose.slides/ihyperlink/action_type/) | Restituisce il tipo dell'azione di HyperLinkEx.<br/>            Solo lettura [`HyperlinkActionType`](/slides/python-net/it/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/it/aspose.slides/ihyperlink/external_url/) | Specifica l'URL esterno<br/>            Se questa proprietà diventa non None allora la proprietà TargetSlide diventa None.<br/>            Solo lettura **str**. |
| [`external_url_original`](/slides/python-net/it/aspose.slides/ihyperlink/external_url_original/) | Rappresenta un collegamento ipertestuale impostato per questa porzione senza considerare il contenuto effettivo della porzione.<br/>            <br/>            PowerPoint si comporta in modo specifico per i collegamenti e il loro testo corrispondente in una porzione. Consente di creare il testo per il collegamento ipertestuale nella forma di un URL valido, diverso dall'indirizzo reale del collegamento. In questo caso, quando visualizzi il collegamento nella finestra di modifica, verrà modificato per corrispondere alla porzione di testo. Questa proprietà rappresenta il valore originale del collegamento ipertestuale. |
| [`target_slide`](/slides/python-net/it/aspose.slides/ihyperlink/target_slide/) | Se HyperlinkEx punta a una diapositiva specifica restituisce questa diapositiva.<br/>            Se la proprietà diventa non None allora la proprietà ExternalUrl diventa None.<br/>            Solo lettura [`ISlide`](/slides/python-net/it/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/it/aspose.slides/ihyperlink/target_frame/) | Restituisce il frame all'interno del frameset HTML padre per il target<br/>            del collegamento ipertestuale padre quando esiste.<br/>            Lettura/scrittura **str**. |
| [`tooltip`](/slides/python-net/it/aspose.slides/ihyperlink/tooltip/) | Restituisce la stringa che può essere visualizzata in un'interfaccia utente<br/>            come associata al collegamento ipertestuale padre.<br/>            Lettura/scrittura **str**. |
| [`history`](/slides/python-net/it/aspose.slides/ihyperlink/history/) | Determina se il target del collegamento ipertestuale padre debba essere aggiunto<br/>            a un elenco di collegamenti ipertestuali visualizzati quando viene invocato.<br/>            Lettura/scrittura **bool**. |
| [`highlight_click`](/slides/python-net/it/aspose.slides/ihyperlink/highlight_click/) | Determina se il collegamento ipertestuale debba essere evidenziato al clic.<br/>            Lettura/scrittura **bool**. |
| [`stop_sound_on_click`](/slides/python-net/it/aspose.slides/ihyperlink/stop_sound_on_click/) | Determina se il suono debba essere interrotto al clic sul collegamento ipertestuale.<br/>            Lettura/scrittura **bool**. |
| [`sound`](/slides/python-net/it/aspose.slides/ihyperlink/sound/) | Rappresenta il suono in riproduzione del collegamento ipertestuale.<br/>            Lettura/scrittura [`IAudio`](/slides/python-net/it/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/it/aspose.slides/ihyperlink/color_source/) | Rappresenta l'origine del colore del collegamento ipertestuale - stile o formato della porzione.<br/>            Lettura/scrittura [`HyperlinkColorSource`](/slides/python-net/it/aspose.slides/hyperlinkcolorsource). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/it/aspose.slides/ihyperlink/equals/#ihyperlink) | Determina se le due istanze Hyperlink sono uguali. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)