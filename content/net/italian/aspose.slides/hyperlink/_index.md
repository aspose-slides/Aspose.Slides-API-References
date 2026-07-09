---
title: Hyperlink
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un hyperlink.
type: docs
weight: 5120
url: /it/aspose.slides/hyperlink/
---
## Hyperlink classe

Rappresenta un hyperlink.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Crea un'istanza di un hyperlink che punta a una diapositiva specifica. Nota: l'hyperlink creato deve essere assegnato a qualche oggetto della stessa presentazione, altrimenti il collegamento verrà salvato come NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Crea un'istanza di un hyperlink. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Crea un'istanza di un hyperlink usando un altro hyperlink come sorgente, sovrascrivendo le proprietà secondarie. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Restituisce un hyperlink che termina la presentazione. Sola lettura [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Restituisce un hyperlink alla prima diapositiva della presentazione. Sola lettura [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Restituisce un hyperlink all'ultima diapositiva della presentazione. Sola lettura [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Restituisce un hyperlink all'ultima diapositiva visualizzata. Sola lettura [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Restituisce un hyperlink speciale “riproduci file multimediale”. Usato in AudioFrame e VideoFrame. Sola lettura [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Restituisce un hyperlink alla diapositiva successiva. Sola lettura [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Restituisce un hyperlink speciale “non fare nulla”. Sola lettura [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Restituisce un hyperlink alla diapositiva precedente. Sola lettura [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Restituisce il tipo di azione dell'Hyperlink. Sola lettura [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. Sola lettura [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Rappresenta la sorgente del colore dell'hyperlink – stili o formattazione della porzione. Lettura/scrittura [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Specifica l'URL esterno. Sola lettura String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Rappresenta un hyperlink impostato per questa porzione senza considerare il contenuto reale della porzione. PowerPoint gestisce in modo specifico i collegamenti e il relativo testo in una porzione. Consente di creare testo per l'hyperlink sotto forma di URL valido, diverso dall'indirizzo reale del collegamento. In questo caso, quando si visualizza il collegamento nella finestra di modifica, verrà modificato per corrispondere alla porzione di testo. Questa proprietà rappresenta il valore originale dell'hyperlink. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Determina se l'hyperlink deve essere evidenziato al clic. Lettura/scrittura Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Determina se il target dell'hyperlink genitore deve essere aggiunto a un elenco di hyperlink visualizzati quando viene invocato. Lettura/scrittura Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Rappresenta il suono di riproduzione dell'hyperlink. Lettura/scrittura [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Determina se il suono deve essere fermato al clic sull'hyperlink. Lettura/scrittura Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Restituisce il frame all'interno del frameset HTML genitore per il target dell'hyperlink genitore quando esiste. Lettura/scrittura String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Se l'Hyperlink punta a una diapositiva specifica restituisce tale diapositiva. Sola lettura [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Restituisce la stringa che può essere mostrata nell'interfaccia utente associata all'hyperlink genitore. Lettura/scrittura String. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Determina se le due istanze Hyperlink sono uguali. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Determina se le due istanze Hyperlink sono uguali. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Funziona come funzione hash per un tipo specifico, adatta all'uso in algoritmi di hashing e strutture dati come una tabella hash. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Verifica l’uguaglianza di due hyperlink. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Verifica la disuguaglianza di due hyperlink. |

### Vedi anche

* classe [PVIObject](../pviobject)
* interfaccia [IHyperlink](../ihyperlink)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->