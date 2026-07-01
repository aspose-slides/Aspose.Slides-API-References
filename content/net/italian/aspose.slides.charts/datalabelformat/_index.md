---
title: DataLabelFormat
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta le opzioni di formattazione per DataLabel.
type: docs
weight: 1550
url: /it/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat classe

Rappresenta le opzioni di formattazione per DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. Solo in lettura [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Restituisce il grafico. Solo in lettura [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Rappresenta il formato dell'etichetta dati. Solo in lettura [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Booleano di lettura/scrittura. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Rappresenta la stringa di formato per l'oggetto DataLabels. Stringa di lettura/scrittura. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Rappresenta la posizione dell'etichetta dati. Lettura/scrittura [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dati su un grafico. Stringa di lettura/scrittura. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. True visualizza il valore della dimensione della bolla. False per nasconderlo. Booleano di lettura/scrittura. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nasconderlo. Booleano di lettura/scrittura. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Determina se l'etichetta dati di un grafico specificato verrà visualizzata come chiamata dati o come etichetta dati. Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelAsDataCallout per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche tale valore sulla proprietà ShowLabelAsDataCallout per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" causa che tutti DataLabels[i].ShowLabelAsDataCallout siano uguali a val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. True visualizza il valore della cella. False per nasconderlo. Booleano di lettura/scrittura. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. True visualizza le linee guida. False per nasconderle. Booleano di lettura/scrittura. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Rappresenta il comportamento di visualizzazione della chiave della legenda dell'etichetta dati di un grafico specificato. True se la chiave della legenda è visibile. Booleano di lettura/scrittura. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nasconderlo. Booleano di lettura/scrittura. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Restituisce o imposta un Booleano per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. True per mostrare il nome della serie. False per nasconderlo. Booleano di lettura/scrittura. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nasconderlo. Booleano di lettura/scrittura. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Restituisce il formato testo del grafico. Solo in lettura [`IChartTextFormat`](../icharttextformat). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Confronta con l'oggetto specificato. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Restituisce il codice hash. |

### Vedi anche

* classe [PVIObject](../../aspose.slides/pviobject)
* interfaccia [IDataLabelFormat](../idatalabelformat)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->