---
title: Hyperlink
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un collegamento ipertestuale.
type: docs
weight: 5100
url: /it/aspose.slides/hyperlink/
---
## Classe Hyperlink

Rappresenta un collegamento ipertestuale.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Crea un'istanza di un collegamento ipertestuale che punta a una diapositiva specifica. Nota: il collegamento ipertestuale creato deve essere assegnato a qualche oggetto della stessa presentazione, altrimenti il collegamento verrà salvato come NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Crea un'istanza di un collegamento ipertestuale. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Crea un'istanza di un collegamento ipertestuale usando un altro collegamento ipertestuale come origine, sovrascrivendo le proprietà secondarie. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Restituisce un collegamento ipertestuale che termina la presentazione. [`Hyperlink`](../hyperlink) {{Solo lettura}}. |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Restituisce un collegamento ipertestuale alla prima diapositiva della presentazione. [`Hyperlink`](../hyperlink) {{Solo lettura}}. |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Restituisce un collegamento ipertestuale all'ultima diapositiva della presentazione. [`Hyperlink`](../hyperlink) {{Solo lettura}}. |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Restituisce un collegamento ipertestuale all'ultima diapositiva visualizzata. [`Hyperlink`](../hyperlink) {{Solo lettura}}. |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Restituisce un collegamento ipertestuale speciale “riproduci file multimediale”. Utilizzato in AudioFrame e VideoFrame. [`Hyperlink`](../hyperlink) {{Solo lettura}}. |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Restituisce un collegamento ipertestuale alla diapositiva successiva. [`Hyperlink`](../hyperlink) {{Solo lettura}}. |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Restituisce un collegamento ipertestuale speciale “non fare nulla”. [`Hyperlink`](../hyperlink) {{Solo lettura}}. |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Restituisce un collegamento ipertestuale alla diapositiva precedente. [`Hyperlink`](../hyperlink) {{Solo lettura}}. |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Restituisce il tipo di azione del collegamento ipertestuale. [`HyperlinkActionType`](../hyperlinkactiontype) {{Solo lettura}}. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. [`IPresentationComponent`](../ipresentationcomponent) {{Solo lettura}}. |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Rappresenta la sorgente del colore del collegamento ipertestuale – stili o formato della porzione. {{Lettura/scrittura}} [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Specifica l'URL esterno. Solo lettura String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Rappresenta un collegamento ipertestuale impostato per questa porzione senza riguardo al contenuto reale della porzione. PowerPoint gestisce in modo specifico i collegamenti e il testo corrispondente in una porzione. Consente di creare testo per il collegamento ipertestuale sotto forma di URL valido, diverso dall'indirizzo reale del collegamento. In questo caso, quando si visualizza il collegamento nella finestra di modifica, verrà modificato per corrispondere alla porzione di testo. Questa proprietà rappresenta il valore originale del collegamento ipertestuale. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Determina se il collegamento ipertestuale deve essere evidenziato al clic. {{Lettura/scrittura}} Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Determina se la destinazione del collegamento ipertestuale genitore deve essere aggiunta a una lista di collegamenti ipertestuali visualizzati quando viene invocata. {{Lettura/scrittura}} Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Rappresenta il suono di riproduzione del collegamento ipertestuale. {{Lettura/scrittura}} [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Determina se il suono deve essere interrotto al clic sul collegamento ipertestuale. {{Lettura/scrittura}} Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Restituisce il frame all'interno del frameset HTML genitore per la destinazione del collegamento ipertestuale genitore, se presente. {{Lettura/scrittura}} String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Se il collegamento ipertestuale punta a una diapositiva specifica, restituisce quella diapositiva. [`ISlide`](../islide) {{Solo lettura}}. |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Restituisce la stringa che può essere mostrata nell'interfaccia utente associata al collegamento ipertestuale genitore. {{Lettura/scrittura}} String. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Determina se due istanze di Hyperlink sono uguali. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Determina se due istanze di Hyperlink sono uguali. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Funziona come una funzione hash per un tipo specifico, idonea per l'uso in algoritmi di hashing e strutture dati come una tabella hash. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Verifica due collegamenti ipertestuali per uguaglianza. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Verifica due collegamenti ipertestuali per disuguaglianza. |

### Vedi anche

* classe [PVIObject](../pviobject)
* interfaccia [IHyperlink](../ihyperlink)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->