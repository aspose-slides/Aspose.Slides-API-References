---
title: IAxis
second_title: Aspose.Slides pro .NET API Reference
description: Zapouzdřuje objekt, který představuje osu grafu.
type: docs
weight: 1710
url: /cs/aspose.slides.charts/iaxis/
---
## IAxis rozhraní

Zapouzdřuje objekt, který představuje osu grafu.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Určuje skutečnou hlavní jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Určuje skutečné měřítko hlavní jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Určuje skutečnou maximální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Určuje skutečnou vedlejší jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Určuje skutečné měřítko vedlejší jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Určuje skutečnou minimální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Zastupuje typ agregace osy kategorií (rozdělování do košů). Používá se pro kategorii. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Umožňuje získat základní rozhraní IFormattedTextContainer. Pouze pro čtení [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost platí pouze pro osy kategorií a nepoužívá se u 3-D grafů. Čtení/zápis Boolovský. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Určuje nejmenší časovou jednotku, která je reprezentována na datumové ose. Čtení/zápis [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Určuje šířku koše, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. Používá se pro osy kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Určuje typ osy kategorií. Čtení/zápis [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Určuje bod na ose, kde ji protichůdná osa protíná. Čtení/zápis Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Určuje CrossType na zadané ose, kde ji protichůdná osa protíná. Čtení/zápis [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Určuje škálovací hodnotu zobrazovacích jednotek pro osu hodnot. Čtení/zápis [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Zastupuje formát osy. Pouze pro čtení [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Určuje, zda má osa viditelný název. Čtení/zápis Boolovský. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Určuje, zda je hlavní jednotka osy přiřazena automaticky. Čtení/zápis Boolovský. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Určuje, zda je maximální hodnota přiřazena automaticky. Čtení/zápis Boolovský. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Určuje, zda je vedlejší jednotka osy přiřazena automaticky. Čtení/zápis Boolovský. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Určuje, zda je minimální hodnota přiřazena automaticky. Čtení/zápis Boolovský. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Určuje automatickou hodnotu přetečné koše. Pokud je false: použijte vlastnost OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Určuje automatickou hodnotu rozestupu popisků značek. Pokud je false: použijte vlastnost TickLabelSpacing. Čtení/zápis Boolovský. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Určuje automatickou hodnotu rozestupu značek. Pokud je false: použijte vlastnost TickMarksSpacing. Čtení/zápis Boolovský. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Určuje automatickou hodnotu podtoku koše. Pokud je false: použijte vlastnost UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Určuje, zda je typ měřítka osy hodnot logaritmický či nikoli. Čtení/zápis Boolovský. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Určuje, zda je formát propojen se zdrojovými daty. Čtení/zápis Boolovský. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Určuje, zda je použita přetečná koš. Použijte IsAutomaticOverflowBin a OverflowBin k úpravě hodnoty přetečné koše. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Určuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. Čtení/zápis Boolovský. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Určuje, zda je použita podtoková koš. Použijte IsAutomaticUnderflowBin a UnderflowBin k úpravě hodnoty podtoku koše. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Určuje, zda je osa viditelná. Čtení/zápis Boolovský. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Určuje vzdálenost popisků od osy. Používá se pro kategorie nebo datumovou osu. Hodnota musí být mezi 0 % a 1000 %. Čtení/zápis UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Zastupuje logaritmickou základnu. Výchozí hodnota je 10. Čtení/zápis Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Zastupuje formát hlavních mřížkových čar na ose grafu. Pouze pro čtení [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Zastupuje typ hlavní značky osy pro zadanou osu. Čtení/zápis [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Zastupuje hlavní jednotky pro datumovou nebo hodnotovou osu. Čtení/zápis Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Zastupuje měřítko hlavní jednotky pro datumovou osu. Čtení/zápis [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Zastupuje maximální hodnotu na ose hodnot. Čtení/zápis Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Zastupuje formát vedlejších mřížkových čar na ose grafu. Pouze pro čtení [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Zastupuje typ vedlejší značky pro zadanou osu. Čtení/zápis [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Zastupuje vedlejší jednotky pro datumovou nebo hodnotovou osu. Čtení/zápis Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Zastupuje měřítko hlavní jednotky pro datumovou osu. Čtení/zápis [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Zastupuje minimální hodnotu na ose hodnot. Čtení/zápis Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Zastupuje řetězec formátu pro popisky osy. Čtení/zápis String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Určuje počet košů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Používá se pro osy kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Určuje vlastní hodnotu přetečné koše. Používá se, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Zastupuje polohu osy. Čtení/zápis [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Zastupuje, zda jsou hlavní mřížkové čáry zobrazeny. Pouze pro čtení Boolovský. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Zastupuje, zda jsou vedlejší mřížkové čáry zobrazeny. Pouze pro čtení Boolovský. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Zastupuje polohu popisků značek na zadané ose. Čtení/zápis [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Zastupuje úhel otočení popisků značek. Čtení/zápis Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Určuje, kolik popisků značek se má přeskočit mezi vykreslenými popisky. Čtení/zápis UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Určuje, kolik značek se má přeskočit před vykreslením další. Používá se pro osu kategorií nebo sérií. Čtení/zápis UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Získá název osy. Pouze pro čtení [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Určuje vlastní hodnotu podtoku koše. Používá se, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true. |

## Metody

| Název | Popis |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Nastaví vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy. |

### Viz také

* rozhraní [IFormattedTextContainer](../iformattedtextcontainer)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->