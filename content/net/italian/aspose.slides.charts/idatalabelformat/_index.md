---
title: IDataLabelFormat
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta le opzioni di formattazione per DataLabel.
type: docs
weight: 2040
url: /it/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat interfaccia

Rappresenta le opzioni di formattazione per DataLabel.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Consente di ottenere l'interfaccia IFormattedTextContainer di base. Solo lettura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Rappresenta il formato dell'etichetta dati. Solo lettura [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Lettura/scrittura Boolean. |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Rappresenta la stringa di formato per l'oggetto DataLabels. Lettura/scrittura String. |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Rappresenta la posizione dell'etichetta dati. Lettura/scrittura [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dati su un grafico. Lettura/scrittura String. |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. True visualizza il valore della dimensione della bolla. False per nasconderlo. Lettura/scrittura Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nasconderlo. Lettura/scrittura Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Determina se l'etichetta dati di un grafico specificato verrà visualizzata come richiamo dati o come etichetta dati. Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelAsDataCallout per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con valore imposta anche questo valore alla proprietà ShowLabelAsDataCallout per tutte le etichette dati nella raccolta DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" cause to all DataLabels[i].ShowLabelAsDataCallout is equal to val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. True visualizza il valore della cella. False per nasconderlo. Lettura/scrittura Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Rappresenta il comportamento di visualizzazione delle linee leader dell'etichetta dati di un grafico specificato. True visualizza le linee leader. False per nasconderle. Lettura/scrittura Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Rappresenta il comportamento di visualizzazione della chiave della leggenda dell'etichetta dati di un grafico specificato. True se la chiave della leggenda dell'etichetta dati è visibile. Lettura/scrittura Boolean. |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nasconderlo. Lettura/scrittura Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Restituisce o imposta un Boolean per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. True per mostrare il nome della serie. False per nasconderlo. Lettura/scrittura Boolean. |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nasconderlo. Lettura/scrittura Boolean. |

### Vedi anche

* interfaccia [IFormattedTextContainer](../iformattedtextcontainer)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->