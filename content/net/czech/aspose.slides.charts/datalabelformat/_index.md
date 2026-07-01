---
title: DataLabelFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Představuje možnosti formátování pro DataLabel.
type: docs
weight: 1550
url: /cs/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat třída

Představuje možnosti formátování pro DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Vrací graf. Pouze pro čtení [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Představuje formát datové popisky. Pouze pro čtení [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Čtení/zápis Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Představuje formátovací řetězec pro objekt DataLabels. Čtení/zápis String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Představuje pozici datové popisky. Čtení/zápis [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Nastavuje nebo vrací Variant představující oddělovač používaný pro datové popisky v grafu. Čtení/zápis String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Představuje chování zobrazení velikosti bubliny datové popisky specifikovaného grafu. True zobrazí hodnotu velikosti bubliny. False pro skrytí. Čtení/zápis Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Představuje chování zobrazení názvu kategorie datové popisky specifikovaného grafu. True zobrazí název kategorie pro datové popisky v grafu. False pro skrytí. Čtení/zápis Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Určuje, zda bude datová popiska specifikovaného grafu zobrazena jako výzva k datům nebo jako datová popiska. Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection sbírka datových popisek, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelAsDataCallout pro nové datové popisky v kolekci DataLabelCollection. Nastavením této vlastnosti na hodnotu se také nastaví tato hodnota vlastnosti ShowLabelAsDataCallout pro všechny datové popisky v kolekci DataLabelCollection (tj. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" způsobí, že všechny DataLabels[i].ShowLabelAsDataCallout budou rovny val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Představuje chování zobrazení hodnoty buňky datové popisky specifikovaného grafu. True zobrazí hodnotu buňky. False pro skrytí. Čtení/zápis Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Představuje chování zobrazení vodicích čar datové popisky specifikovaného grafu. True zobrazí vodicí čáry. False pro skrytí. Čtení/zápis Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Představuje chování zobrazení legendárního klíče datové popisky specifikovaného grafu. True pokud je legendární klíč datové popisky viditelný. Čtení/zápis Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Představuje chování zobrazení procentuální hodnoty datové popisky specifikovaného grafu. True zobrazí procentuální hodnotu. False pro skrytí. Čtení/zápis Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Vrací nebo nastavuje Boolean, který určuje chování zobrazení názvu řady pro datové popisky v grafu. True pro zobrazení názvu řady. False pro skrytí. Čtení/zápis Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Představuje chování zobrazení procentuální hodnoty datové popisky specifikovaného grafu. True zobrazí procentuální hodnotu. False pro skrytí. Čtení/zápis Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Vrací formát textu grafu. Pouze pro čtení [`IChartTextFormat`](../icharttextformat). |

## Metody

| Název | Popis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává s určeným objektem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Viz také

* třída [PVIObject](../../aspose.slides/pviobject)
* rozhraní [IDataLabelFormat](../idatalabelformat)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->