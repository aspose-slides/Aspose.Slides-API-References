---
title: DataLabel
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta le etichette di una serie.
type: docs
weight: 1560
url: /it/aspose.slides.charts/datalabel/
---
## DataLabel classe

Rappresenta le etichette di una serie.

```csharp
public class DataLabel : IDataLabel
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DataLabel](datalabel)(IChartDataPoint) | Crea una nuova istanza della classe DataLabel. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/datalabel/actualheight) { get; } | Specifica l'altezza effettiva dell'elemento del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Lettura Single. |
| [ActualWidth](../../aspose.slides.charts/datalabel/actualwidth) { get; } | Specifica la larghezza effettiva dell'elemento del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Lettura Single. |
| [ActualX](../../aspose.slides.charts/datalabel/actualx) { get; } | Specifica la posizione x effettiva (sinistra) dell'elemento del grafico rispetto all'angolo in alto a sinistra del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Lettura Single. |
| [ActualY](../../aspose.slides.charts/datalabel/actualy) { get; } | Specifica la posizione superiore effettiva dell'elemento del grafico rispetto all'angolo in alto a sinistra del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Lettura Single. |
| [Bottom](../../aspose.slides.charts/datalabel/bottom) { get; } | Inferiore. Solo lettura Single. |
| [Chart](../../aspose.slides.charts/datalabel/chart) { get; } | Restituisce il grafico padre. Solo lettura [`IChart`](../ichart). |
| [DataLabelFormat](../../aspose.slides.charts/datalabel/datalabelformat) { get; } | Restituisce il formato dell'etichetta dati. Solo lettura [`IDataLabelFormat`](../idatalabelformat). |
| [Height](../../aspose.slides.charts/datalabel/height) { get; set; } | Restituisce o imposta l'altezza di un titolo come frazione dell'altezza del grafico. Lettura/scrittura Single. |
| [IsVisible](../../aspose.slides.charts/datalabel/isvisible) { get; } | False indica che l'etichetta dati non è visibile (e quindi tutti i flag Show* (ShowValue, ...) sono falsi). Solo lettura Boolean. |
| [LabelShapeType](../../aspose.slides.charts/datalabel/labelshapetype) { get; set; } | Ottiene o imposta il tipo di forma dell'etichetta dati. Restituisce NotDefined se non è definita alcuna forma. |
| [Right](../../aspose.slides.charts/datalabel/right) { get; } | Destro. Solo lettura Single. |
| [TextFormat](../../aspose.slides.charts/datalabel/textformat) { get; } | Restituisce il formato del testo. Solo lettura [`IChartTextFormat`](../icharttextformat). |
| [TextFrameForOverriding](../../aspose.slides.charts/datalabel/textframeforoverriding) { get; } | Può contenere un testo riccamente formattato. Se questa proprietà non è nulla, allora questo valore di testo formattato sovrascrive il testo auto-generato dell'etichetta dati. Il testo auto-generato dell'etichetta dati indica il testo gestito dalle proprietà ShowSeriesName, ShowValue, ... e formattato con la proprietà TextFormatManager.TextFormat. Solo lettura [`ITextFrame`](../../aspose.slides/itextframe). |
| [ValueFromCell](../../aspose.slides.charts/datalabel/valuefromcell) { get; set; } | Ottiene o imposta la cella dati della cartella di lavoro. Applicato se la proprietà IDataLabelFormat.ShowLabelValueFromCell è true. |
| [Width](../../aspose.slides.charts/datalabel/width) { get; set; } | Restituisce o imposta la larghezza di un titolo come frazione della larghezza del grafico. Lettura/scrittura Single. |
| [X](../../aspose.slides.charts/datalabel/x) { get; set; } | Restituisce o imposta la coordinata x di un titolo come frazione della larghezza del grafico. Lettura/scrittura Single. |
| [Y](../../aspose.slides.charts/datalabel/y) { get; set; } | Restituisce o imposta la coordinata y di un titolo come frazione dell'altezza del grafico. Lettura/scrittura Single. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/datalabel/addtextframeforoverriding)(string) | Inizializza TextFrameForOverriding con il testo nel parametro "text". Se TextFrameForOverriding è già inizializzato, cambia semplicemente il suo testo. |
| [GetActualLabelText](../../aspose.slides.charts/datalabel/getactuallabeltext)() | Restituisce il testo effettivo dell'etichetta basato sulle impostazioni di DataLabelFormat o sul valore TextFrameForOverriding.Text. |
| [Hide](../../aspose.slides.charts/datalabel/hide)() | Rende l'etichetta dati nascosta impostando tutti i flag Show* (ShowValue, ...) su false. IsVisible sarà false dopo questa operazione. |

### Vedi anche

* interfaccia [IDataLabel](../idatalabel)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->