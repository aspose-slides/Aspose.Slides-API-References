---
title: IDataLabelFormat
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt de opmaakopties voor DataLabel voor.
type: docs
weight: 2040
url: /nl/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat interface

Stelt een interface voor met opmaakopties voor DataLabel.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Staat toe om de basis IFormattedTextContainer interface op te halen. Alleen-lezen [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Representeert het formaat van het gegevenslabel. Alleen-lezen [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Lezen/schrijven Boolean. |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Representeert de opmaakreeks voor het DataLabels-object. Lezen/schrijven String. |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Representeert de positie van het gegevenslabel. Lezen/schrijven [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Stelt een Variant in of retourneert deze, die de scheidingsteken vertegenwoordigt dat wordt gebruikt voor de gegevenslabels op een grafiek. Lezen/schrijven String. |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Representeert het weergavegedrag van de bubbelaanzeed-waarde van het gegevenslabel van een opgegeven grafiek. True geeft de bubbelaanzeed-waarde weer. False verbergt deze. Lezen/schrijven Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Representeert het weergavegedrag van de categorienaam van het gegevenslabel van een opgegeven grafiek. True om de categorienaam weer te geven voor de gegevenslabels op een grafiek. False om te verbergen. Lezen/schrijven Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Bepaalt of het gegevenslabel van een opgegeven grafiek wordt weergegeven als data callout of als gegevenslabel. Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLabelAsDataCallout-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Stel deze eigenschap in met een waarde, dan wordt deze waarde ook ingesteld op de ShowLabelAsDataCallout-eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" waardoor alle DataLabels[i].ShowLabelAsDataCallout gelijk zijn aan val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Representeert het weergavegedrag van de celwaarde van het gegevenslabel van een opgegeven grafiek. True geeft de celwaarde weer. False verbergt deze. Lezen/schrijven Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Representeert het weergavegedrag van de leidende lijnen van het gegevenslabel van een opgegeven grafiek. True geeft de leidende lijnen weer. False verbergt deze. Lezen/schrijven Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Representeert het weergavegedrag van de legende-sleutel van het gegevenslabel van een opgegeven grafiek. True als de legende-sleutel van het gegevenslabel zichtbaar is. Lezen/schrijven Boolean. |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Representeert het weergavegedrag van de procentwaarde van het gegevenslabel van een opgegeven grafiek. True geeft de procentwaarde weer. False verbergt deze. Lezen/schrijven Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Geeft een Boolean terug of stelt deze in om het weergavegedrag van de serienaam voor de gegevenslabels op een grafiek aan te geven. True om de serienaam weer te geven. False om te verbergen. Lezen/schrijven Boolean. |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Representeert het weergavegedrag van de procentwaarde van het gegevenslabel van een opgegeven grafiek. True geeft de procentwaarde weer. False verbergt deze. Lezen/schrijven Boolean. |

### Zie ook

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->