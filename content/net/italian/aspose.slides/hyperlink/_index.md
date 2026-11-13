---
title: Hyperlink
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un collegamento ipertestuale.
type: docs
weight: 5140
url: /it/aspose.slides/hyperlink/
---
## classe Hyperlink

Rappresenta un collegamento ipertestuale.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Crea un'istanza di un collegamento ipertestuale che punta a una diapositiva specifica. Nota: il collegamento ipertestuale creato deve essere assegnato a un oggetto della stessa presentazione, altrimenti il collegamento verrà salvato come NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Crea un'istanza di un collegamento ipertestuale. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Crea un'istanza di un collegamento ipertestuale usando un altro collegamento ipertestuale come sorgente, sovrascrivendo le proprietà secondarie. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Restituisce un collegamento ipertestuale che termina la presentazione. Solo lettura [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Restituisce un collegamento ipertestuale alla prima diapositiva della presentazione. Solo lettura [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Restituisce un collegamento ipertestuale all'ultima diapositiva della presentazione. Solo lettura [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Restituisce un collegamento ipertestuale all'ultima diapositiva visualizzata. Solo lettura [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Restituisce un collegamento ipertestuale speciale "play mediafile". Usato in AudioFrame e VideoFrame. Solo lettura [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Restituisce un collegamento ipertestuale alla diapositiva successiva. Solo lettura [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Restituisce un collegamento ipertestuale speciale "do nothing". Solo lettura [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Restituisce un collegamento ipertestuale alla diapositiva precedente. Solo lettura [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Restituisce il tipo di azione del collegamento ipertestuale. Solo lettura [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. Solo lettura [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Rappresenta la sorgente del colore del collegamento ipertestuale – stili o formato della porzione. Lettura/scrittura [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Specifica l'URL esterno. Solo lettura String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Rappresenta un collegamento ipertestuale impostato per questa porzione senza considerare il contenuto reale della porzione. PowerPoint gestisce specificamente i collegamenti e il testo corrispondente in una porzione. Consente di creare il testo per il collegamento ipertestuale sotto forma di URL valido, diverso dall'indirizzo reale del collegamento. In questo caso, quando si visualizza il collegamento nella finestra di modifica, verrà modificato per corrispondere al testo della porzione. Questa proprietà rappresenta il valore originale del collegamento ipertestuale. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Determina se il collegamento ipertestuale deve essere evidenziato al clic. Lettura/scrittura Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Determina se il target del collegamento ipertestuale genitore deve essere aggiunto a un elenco di collegamenti ipertestuali visualizzati quando viene invocato. Lettura/scrittura Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Rappresenta il suono di riproduzione del collegamento ipertestuale. Lettura/scrittura [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Determina se il suono deve essere interrotto al clic sul collegamento ipertestuale. Lettura/scrittura Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Restituisce il frame all'interno del frameset HTML genitore per il target del collegamento ipertestuale genitore quando ne esiste uno. Lettura/scrittura String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Se il collegamento ipertestuale punta a una diapositiva specifica, restituisce tale diapositiva. Solo lettura [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Restituisce la stringa che può essere mostrata in un'interfaccia utente associata al collegamento ipertestuale genitore. Lettura/scrittura String. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Determina se le due istanze di Hyperlink sono uguali. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Determina se le due istanze di Hyperlink sono uguali. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Funziona come funzione hash per un tipo specifico, idonea per l'uso in algoritmi di hashing e strutture dati come una tabella hash. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Verifica l'uguaglianza di due collegamenti ipertestuali. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Verifica la disuguaglianza di due collegamenti ipertestuali. |

### Vedi anche

* classe [PVIObject](../pviobject)
* interfaccia [IHyperlink](../ihyperlink)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->