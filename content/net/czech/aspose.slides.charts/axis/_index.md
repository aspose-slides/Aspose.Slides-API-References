---
title: Axis
second_title: Aspose.Sildes pro .NET API referenci
description: Zapouzdřuje objekt, který představuje osu grafu.
type: docs
weight: 1180
url: /cs/aspose.slides.charts/axis/
---
## Axis třída

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Určuje skutečnou hlavní jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Určuje skutečnou stupnici hlavní jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Určuje skutečnou maximální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Určuje skutečnou podružnou jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Určuje skutečnou stupnici podružné jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Určuje skutečnou minimální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Reprezentuje typ agregace kategoriální osy (seskupování). Použito pro kategorie. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Reprezentuje, zda osa hodnot protíná kategoriální osu mezi kategoriemi. Tato vlastnost platí pouze pro kategoriální osy a neuplatňuje se u 3-D grafů. Čtení/zápis Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Určuje nejmenší časovou jednotku, která je zobrazena na časové ose. Čtení/zápis [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Určuje šířku koše, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. Použito pro kategoriální osy. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Určuje typ kategoriální osy. Čtení/zápis [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Vrací nadřazený graf. Pouze ke čtení [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Reprezentuje bod na ose, kde ji protichůdná osa protíná. Čtení/zápis Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Reprezentuje CrossType na dané ose, kde ji protichůdná osa protíná. Čtení/zápis [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Určuje škálovací hodnotu zobrazovacích jednotek pro osu hodnot. Čtení/zápis [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Reprezentuje formát osy. Pouze ke čtení [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Určuje, zda osa má viditelný název. Čtení/zápis Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Uvádí, zda je hlavní jednotka osy přiřazena automaticky. Čtení/zápis Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Uvádí, zda je maximální hodnota přiřazena automaticky. Čtení/zápis Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Uvádí, zda je podružná jednotka osy přiřazena automaticky. Čtení/zápis Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Uvádí, zda je minimální hodnota přiřazena automaticky. Čtení/zápis Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Určuje automatickou hodnotu přetečujícího koše. Pokud nepravda: použijte vlastnost OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Určuje automatickou hodnotu rozestupu popisků značek. Pokud nepravda: použijte vlastnost TickLabelSpacing. Čtení/zápis Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Určuje automatickou hodnotu rozestupu značek. Pokud nepravda: použijte vlastnost TickMarksSpacing. Čtení/zápis Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Určuje automatickou hodnotu podtečného koše. Pokud nepravda: použijte vlastnost UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Reprezentuje, zda je typ měřítka osy hodnot logaritmický či nikoli. Čtení/zápis Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Uvádí, zda je formát propojen se zdrojovými daty. Čtení/zápis Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Určuje, zda je použit přetečný koš. K úpravě hodnoty přetečného koše použijte IsAutomaticOverflowBin a OverflowBin. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Reprezentuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. Čtení/zápis Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Určuje, zda je použit podtečný koš. K úpravě hodnoty podtečného koše použijte IsAutomaticUnderflowBin a UnderflowBin. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Reprezentuje, zda je osa viditelná. Čtení/zápis Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Určuje vzdálenost popisků od osy. Použito pro kategoriální nebo časovou osu. Hodnota musí být mezi 0 % a 1000 %. Čtení/zápis UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Reprezentuje logaritmickou základnu. Výchozí hodnota je 10. Čtení/zápis Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Reprezentuje formát hlavních mřížkových čar na ose grafu. Pouze ke čtení [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Reprezentuje typ hlavní značky pro zadanou osu. Čtení/zápis [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Reprezentuje hlavní jednotky pro časovou nebo hodnotovou osu. Čtení/zápis Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Reprezentuje stupnici hlavní jednotky pro časovou osu. Čtení/zápis [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Reprezentuje maximální hodnotu na ose hodnot. Čtení/zápis Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Reprezentuje formát podružných mřížkových čar na ose grafu. Pouze ke čtení [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Reprezentuje typ podružné značky pro zadanou osu. Čtení/zápis [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Reprezentuje podružné jednotky pro časovou nebo hodnotovou osu. Čtení/zápis Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Reprezentuje stupnici hlavní jednotky pro časovou osu. Čtení/zápis [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Reprezentuje minimální hodnotu na ose hodnot. Čtení/zápis Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Reprezentuje formátovací řetězec pro popisky osy. Čtení/zápis String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Určuje počet košů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Použito pro kategoriální osy. Používá se pouze se sériemi Histogram nebo HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Určuje vlastní hodnotu přetečného koše. Použito, když je vlastnost IsAutomaticOverflowBin nastavena na nepravda a vlastnost IsOverflowBin je pravda. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Reprezentuje polohu osy. Čtení/zápis [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Pro skrytí hlavní mřížkové čáry nastavte MajorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Pouze ke čtení Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Pro skrytí podružné mřížkové čáry nastavte MinorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Pouze ke čtení Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Reprezentuje formát textu. Pouze ke čtení [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Reprezentuje polohu popisků značek na zadané ose. Čtení/zápis [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Reprezentuje úhel otáčení popisků značek. Čtení/zápis Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Určuje, kolik popisků značek se má přeskočit mezi vykreslenými popisky. Použito pro kategoriální nebo sériovou osu. Čtení/zápis UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Určuje, kolik značek má být přeskočeno před vykreslením další. Použito pro kategoriální nebo sériovou osu. Čtení/zápis UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Získává název osy. Pouze ke čtení [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Určuje vlastní hodnotu podtečného koše. Použito, když je vlastnost IsAutomaticUnderflowBin nastavena na nepravda a vlastnost IsUnderflowBin je pravda. |

## Metody

| Název | Popis |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Nastaví vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy. |

### Viz také

* třída [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* třída [AxesManager](../axesmanager)
* rozhraní [IAxis](../iaxis)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->