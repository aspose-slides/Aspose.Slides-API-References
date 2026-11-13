---
title: DataLabelFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje možnosti formátování pro DataLabel.
type: docs
weight: 1580
url: /cs/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat třída

Reprezentuje možnosti formátování pro DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze ke čtení [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Vrací graf. Pouze ke čtení [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Reprezentuje formát popisku dat. Pouze ke čtení [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Čtení/zápis Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Reprezentuje řetězec formátu pro objekt DataLabels. Čtení/zápis String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Reprezentuje pozici popisku dat. Čtení/zápis [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Nastavuje nebo vrací Variant představující oddělovač používaný pro popisky dat v grafu. Čtení/zápis String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Reprezentuje chování zobrazování hodnoty velikosti bubliny popisku dat v konkrétním grafu. True zobrazuje hodnotu velikosti bubliny. False skrývá. Čtení/zápis Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Reprezentuje chování zobrazování názvu kategorie popisku dat v konkrétním grafu. True zobrazí název kategorie. False skrývá. Čtení/zápis Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Určuje, zda bude popisek dat v daném grafu zobrazen jako výzva k datům nebo jako popisek dat. Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelAsDataCallout pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti na hodnotu se také nastaví tato hodnota pro vlastnost ShowLabelAsDataCallout pro všechny popisky dat v kolekci DataLabelCollection (tj. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" způsobí, že všechny DataLabels[i].ShowLabelAsDataCallout jsou rovny val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Reprezentuje chování zobrazování hodnoty buňky popisku dat v konkrétním grafu. True zobrazuje hodnotu buňky. False skrývá. Čtení/zápis Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Reprezentuje chování zobrazování čar vedoucích popisek dat v konkrétním grafu. True zobrazí čáry. False skrývá. Čtení/zápis Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Reprezentuje chování zobrazování klíče legendy popisku dat v konkrétním grafu. True pokud je klíč legendy viditelný. Čtení/zápis Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Reprezentuje chování zobrazování procentuální hodnoty popisku dat v konkrétním grafu. True zobrazuje procentuální hodnotu. False skrývá. Čtení/zápis Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Vrací nebo nastaví Boolean, který určuje, zda se na popiscích dat v grafu zobrazí název řady. True zobrazí název řady. False skrývá. Čtení/zápis Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Reprezentuje chování zobrazování procentuální hodnoty popisku dat v konkrétním grafu. True zobrazuje procentuální hodnotu. False skrývá. Čtení/zápis Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Vrací formát textu grafu. Pouze ke čtení [`IChartTextFormat`](../icharttextformat). |

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