---
title: IAxis
second_title: Aspose.Sildes pro .NET API Reference
description: Zapouzdřuje objekt, který představuje osu grafu.
type: docs
weight: 1690
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
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Určuje aktuální hlavní jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Určuje aktuální měřítko hlavní jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Určuje aktuální maximální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Určuje aktuální vedlejší jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Určuje aktuální měřítko vedlejší jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Určuje aktuální minimální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Reprezentuje typ agregace osy kategorií (seskupování). Používá se pro kategorie. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Umožňuje získat základní rozhraní IFormattedTextContainer. Pouze pro čtení [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost se vztahuje pouze na osy kategorií a neplatí pro 3-D grafy. Čtení/Zápis Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Určuje nejmenší časovou jednotku, která je zobrazena na časové ose. Čtení/Zápis [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Určuje šířku binu, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. Používá se pro osy kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Určuje typ osy kategorií. Čtení/Zápis [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Reprezentuje bod na ose, kde ji protíná kolmá osa. Čtení/Zápis Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Reprezentuje typ průniku (CrossType) na zadané ose, kde ji protíná druhá osa. Čtení/Zápis [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Určuje měřítkovou hodnotu zobrazovacích jednotek pro osu hodnot. Čtení/Zápis [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Reprezentuje formát osy. Pouze pro čtení [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Určuje, zda má osa viditelný název. Čtení/Zápis Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indikuje, zda je hlavní jednotka osy přiřazena automaticky. Čtení/Zápis Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indikuje, zda je maximální hodnota přiřazena automaticky. Čtení/Zápis Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indikuje, zda je vedlejší jednotka osy přiřazena automaticky. Čtení/Zápis Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indikuje, zda je minimální hodnota přiřazena automaticky. Čtení/Zápis Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Určuje automatickou hodnotu overflow binu. Pokud je false: použijte vlastnost OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Určuje automatickou hodnotu rozestupu popisků značek. Pokud je false: použijte vlastnost TickLabelSpacing. Čtení/Zápis Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Určuje automatickou hodnotu rozestupu značek. Pokud je false: použijte vlastnost TickMarksSpacing. Čtení/Zápis Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Určuje automatickou hodnotu underflow binu. Pokud je false: použijte vlastnost UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Reprezentuje, zda je typ měřítka osy hodnot logaritmický nebo ne. Čtení/Zápis Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indikuje, zda je formát propojen se zdrojovými daty. Čtení/Zápis Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Určuje, zda je použit overflow bin. Použijte IsAutomaticOverflowBin a OverflowBin pro úpravu hodnoty overflow binu. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Reprezentuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. Čtení/Zápis Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Určuje, zda je použit underflow bin. Použijte IsAutomaticUnderflowBin a UnderflowBin pro úpravu hodnoty underflow binu. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Reprezentuje, zda je osa viditelná. Čtení/Zápis Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Určuje vzdálenost popisků od osy. Používá se pro osu kategorií nebo datum. Hodnota musí být mezi 0 % a 1000 %. Čtení/Zápis UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Reprezentuje logaritmickou základnu. Výchozí hodnota je 10. Čtení/Zápis Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Reprezentuje formát hlavních mřížkových čar na ose grafu. Pouze pro čtení [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Reprezentuje typ hlavní značky na zadané ose. Čtení/Zápis [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Reprezentuje hlavní jednotky pro osu datum nebo hodnotu. Čtení/Zápis Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Reprezentuje měřítko hlavní jednotky pro osu datum. Čtení/Zápis [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Reprezentuje maximální hodnotu na ose hodnot. Čtení/Zápis Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Reprezentuje formát vedlejších mřížkových čar na ose grafu. Pouze pro čtení [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Reprezentuje typ vedlejší značky na zadané ose. Čtení/Zápis [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Reprezentuje vedlejší jednotky pro osu datum nebo hodnotu. Čtení/Zápis Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Reprezentuje měřítko hlavní jednotky pro osu datum. Čtení/Zápis [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Reprezentuje minimální hodnotu na ose hodnot. Čtení/Zápis Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Reprezentuje řetězec formátu pro popisky osy. Čtení/Zápis String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Určuje počet binů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Používá se pro osy kategorií. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Určuje uživatelskou hodnotu overflow binu. Používá se, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Reprezentuje pozici osy. Čtení/Zápis [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Reprezentuje, zda jsou zobrazeny hlavní mřížkové čáry. Pouze pro čtení Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Reprezentuje, zda jsou zobrazeny vedlejší mřížkové čáry. Pouze pro čtení Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Reprezentuje pozici popisků značkových čar na zadané ose. Čtení/Zápis [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Reprezentuje úhel otočení popisků značek. Čtení/Zápis Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Určuje, kolik popisků značek přeskočit mezi zobrazenými popisky. Čtení/Zápis UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Určuje, kolik značek má být přeskočeno před vykreslením další. Používá se pro osu kategorií nebo sérií. Čtení/Zápis UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Získá název osy. Pouze pro čtení [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Určuje uživatelskou hodnotu underflow binu. Používá se, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true. |

## Metody

| Název | Popis |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Nastaví vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy. |

### Viz také

* rozhraní [IFormattedTextContainer](../iformattedtextcontainer)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->