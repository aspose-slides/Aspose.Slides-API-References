---
title: IAxis
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Zapouzdřuje objekt, který představuje osu grafu.
type: docs
weight: 1720
url: /cs/aspose.slides.charts/iaxis/
---
## IAxis rozhraní

Encapsulates the object that represents a chart's axis.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Určuje aktuální hlavní jednotku osy. Nejprve zavolejte metodu IChart.ValidateChartLayout(), abyste získali aktuální hodnotu. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Určuje aktuální měřítko hlavní jednotky osy. Nejprve zavolejte metodu IChart.ValidateChartLayout(), abyste získali aktuální hodnotu. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Určuje aktuální maximální hodnotu na ose. Nejprve zavolejte metodu IChart.ValidateChartLayout(), abyste získali aktuální hodnotu. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Určuje aktuální vedlejší jednotku osy. Nejprve zavolejte metodu IChart.ValidateChartLayout(), abyste získali aktuální hodnotu. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Určuje aktuální měřítko vedlejší jednotky osy. Nejprve zavolejte metodu IChart.ValidateChartLayout(), abyste získali aktuální hodnotu. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Určuje aktuální minimální hodnotu na ose. Nejprve zavolejte metodu IChart.ValidateChartLayout(), abyste získali aktuální hodnotu. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Reprezentuje typ agregace kategoriální osy (rozdělení do košů). Používá se pro kategorie. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Umožňuje získat základní rozhraní IFormattedTextContainer. Pouze pro čtení [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Určuje, zda osa hodnot protíná kategoriální osu mezi kategoriemi. Tato vlastnost platí pouze pro kategoriální osy a neplatí pro 3D grafy. Čtení/zápis Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Určuje nejmenší časovou jednotku zobrazovanou na časové ose. Čtení/zápis [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Určuje šířku koše, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. Používá se pro kategoriální osy. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Určuje typ kategoriální osy. Čtení/zápis [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Určuje bod na ose, kde ji protne kolmá osa. Čtení/zápis Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Určuje typ průseku (CrossType) na zadané ose, kde ji protíná druhá osa. Čtení/zápis [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Určuje měřítko zobrazovacích jednotek pro osu hodnot. Čtení/zápis [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Reprezentuje formát osy. Pouze pro čtení [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Určuje, zda má osa viditelný název. Čtení/zápis Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Udává, zda je hlavní jednotka osy přiřazena automaticky. Čtení/zápis Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Udává, zda je maximální hodnota přiřazena automaticky. Čtení/zápis Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Udává, zda je vedlejší jednotka osy přiřazena automaticky. Čtení/zápis Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Udává, zda je minimální hodnota přiřazena automaticky. Čtení/zápis Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Určuje automatickou hodnotu přetečení koše. Pokud ne, použijte vlastnost OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Určuje automatickou hodnotu rozestupu popisků značek. Pokud ne, použijte vlastnost TickLabelSpacing. Čtení/zápis Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Určuje automatickou hodnotu rozestupu značek. Pokud ne, použijte vlastnost TickMarksSpacing. Čtení/zápis Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Určuje automatickou hodnotu podtečení koše. Pokud ne, použijte vlastnost UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Určuje, zda je typ měřítka osy hodnot logaritmický. Čtení/zápis Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Udává, zda je formát propojený se zdrojovými daty. Čtení/zápis Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Určuje, zda je použita přetečná nádoba. Použijte IsAutomaticOverflowBin a OverflowBin k úpravě hodnoty přetečného koše. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Určuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. Čtení/zápis Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Určuje, zda je použita podtečná nádoba. Použijte IsAutomaticUnderflowBin a UnderflowBin k úpravě hodnoty podtečného koše. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Určuje, zda je osa viditelná. Čtení/zápis Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Určuje vzdálenost popisků od osy. Používá se pro kategoriální nebo časovou osu. Hodnota musí být mezi 0 % a 1000 %. Čtení/zápis UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Reprezentuje logaritmickou základnu. Výchozí hodnota je 10. Čtení/zápis Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Reprezentuje formát hlavních mřížkových čar na ose grafu. Pouze pro čtení [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Určuje typ hlavní značky pro zadanou osu. Čtení/zápis [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Určuje hlavní jednotky pro časovou nebo hodnotovou osu. Čtení/zápis Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Určuje měřítko hlavní jednotky pro časovou osu. Čtení/zápis [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Určuje maximální hodnotu na ose hodnot. Čtení/zápis Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Reprezentuje formát vedlejších mřížkových čar na ose grafu. Pouze pro čtení [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Určuje typ vedlejší značky pro zadanou osu. Čtení/zápis [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Určuje vedlejší jednotky pro časovou nebo hodnotovou osu. Čtení/zápis Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Určuje měřítko hlavní jednotky pro časovou osu. Čtení/zápis [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Určuje minimální hodnotu na ose hodnot. Čtení/zápis Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Určuje řetězec formátu pro popisky osy. Čtení/zápis String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Určuje počet košů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Používá se pro kategoriální osy. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Určuje vlastní hodnotu přetečného koše. Používá se, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Určuje pozici osy. Čtení/zápis [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Určuje, zda jsou zobrazeny hlavní mřížkové čáry. Pouze pro čtení Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Určuje, zda jsou zobrazeny vedlejší mřížkové čáry. Pouze pro čtení Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Určuje pozici popisků značek na zadané ose. Čtení/zápis [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Určuje úhel otáčení popisků značek. Čtení/zápis Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Určuje, kolik popisků značek se má přeskočit mezi vykreslenými popisky. Čtení/zápis UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Určuje, kolik značek se má přeskočit před vykreslením další. Používá se pro kategoriální nebo sériovou osu. Čtení/zápis UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Získává název osy. Pouze pro čtení [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Určuje vlastní hodnotu podtečného koše. Používá se, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true. |

## Metody

| Název | Popis |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Nastaví vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy. |

### Viz také

* rozhraní [IFormattedTextContainer](../iformattedtextcontainer)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->