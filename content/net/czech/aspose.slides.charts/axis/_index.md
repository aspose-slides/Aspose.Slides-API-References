---
title: Axis
second_title: Aspose.Sildes pro .NET API referenci
description: Zapouzdřuje objekt, který představuje osu grafu.
type: docs
weight: 1160
url: /cs/aspose.slides.charts/axis/
---
## Axis třída

Encapsulates the object that represents a chart's axis.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Udává skutečnou hlavní jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Udává skutečné měřítko hlavní jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Udává skutečnou maximální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Udává skutečnou vedlejší jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Udává skutečné měřítko vedlejší jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Udává skutečnou minimální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Reprezentuje typ agregace osy kategorie (rozdělení do košů). Použito pro kategorii. Použito pouze se sériemi Histogram nebo HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Reprezentuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost platí pouze pro osy kategorií a neplatí pro 3-D diagramy. Číst/Zapisovat Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Udává nejmenší časovou jednotku reprezentovanou na datové ose. Číst/Zapisovat [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Udává šířku koše, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. Použito pro osy kategorií. Použito pouze se sériemi Histogram nebo HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Udává typ osy kategorie. Číst/Zapisovat [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Vrací nadřazený graf. Pouze ke čtení [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Reprezentuje bod na ose, kde ji protichůdná osa protíná. Číst/Zapisovat Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Reprezentuje CrossType na zadané ose, kde ji protichůdná osa protíná. Číst/Zapisovat [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Udává škálovací hodnotu zobrazovacích jednotek pro osu hodnot. Číst/Zapisovat [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Reprezentuje formát osy. Pouze ke čtení [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Určuje, zda má osa viditelný název. Číst/Zapisovat Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indikuje, zda je hlavní jednotka osy přiřazena automaticky. Číst/Zapisovat Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indikuje, zda je maximální hodnota přiřazena automaticky. Číst/Zapisovat Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indikuje, zda je vedlejší jednotka osy přiřazena automaticky. Číst/Zapisovat Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indikuje, zda je minimální hodnota přiřazena automaticky. Číst/Zapisovat Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Udává automatickou hodnotu přetečného koše. Pokud ne: použijte vlastnost OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Udává automatickou hodnotu mezery popisků značek. Pokud ne: použijte vlastnost TickLabelSpacing. Číst/Zapisovat Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Udává automatickou hodnotu mezery značek. Pokud ne: použijte vlastnost TickMarksSpacing. Číst/Zapisovat Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Udává automatickou hodnotu podtečného koše. Pokud ne: použijte vlastnost UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Reprezentuje, zda je typ měřítka osy hodnot logaritmický nebo ne. Číst/Zapisovat Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indikuje, zda je formát propojen s daty zdroje. Číst/Zapisovat Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Udává, zda je použit přetečný koš. Použijte IsAutomaticOverflowBin a OverflowBin k úpravě hodnoty přetečného koše. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Reprezentuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. Číst/Zapisovat Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Udává, zda je použit podtečný koš. Použijte IsAutomaticUnderflowBin a UnderflowBin k úpravě hodnoty podtečného koše. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Reprezentuje, zda je osa viditelná. Číst/Zapisovat Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Udává vzdálenost popisků od osy. Použito pro osy kategorií nebo data. Hodnota musí být mezi 0 % a 1000 %. Číst/Zapisovat UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Reprezentuje logaritmickou základnu. Výchozí hodnota je 10. Číst/Zapisovat Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Reprezentuje formát hlavních mřížkových čar na ose diagramu. Pouze ke čtení [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Reprezentuje typ hlavní značky pro zadanou osu. Číst/Zapisovat [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Reprezentuje hlavní jednotky pro datovou nebo hodnotovou osu. Číst/Zapisovat Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Reprezentuje měřítko hlavní jednotky pro datovou osu. Číst/Zapisovat [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Reprezentuje maximální hodnotu na ose hodnot. Číst/Zapisovat Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Reprezentuje formát vedlejších mřížkových čar na ose diagramu. Pouze ke čtení [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Reprezentuje typ vedlejší značky pro zadanou osu. Číst/Zapisovat [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Reprezentuje vedlejší jednotky pro datovou nebo hodnotovou osu. Číst/Zapisovat Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Reprezentuje měřítko hlavní jednotky pro datovou osu. Číst/Zapisovat [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Reprezentuje minimální hodnotu na ose hodnot. Číst/Zapisovat Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Reprezentuje řetězec formátu pro popisky osy. Číst/Zapisovat String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Udává počet košů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Použito pro osy kategorií. Použito pouze se sériemi Histogram nebo HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Udává vlastní hodnotu přetečného koše. Použito, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Reprezentuje pozici osy. Číst/Zapisovat [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Pro skrytí hlavní mřížkové čáry nastavte MajorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Pouze ke čtení Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Pro skrytí vedlejší mřížkové čáry nastavte MinorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Pouze ke čtení Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Reprezentuje formát textu. Pouze ke čtení [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Reprezentuje umístění popisků značek na zadané ose. Číst/Zapisovat [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Reprezentuje úhel otočení popisků značek. Číst/Zapisovat Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Udává, kolik popisků značek přeskočit mezi vykreslenými popisky. Použito pro osy kategorií nebo sérií. Číst/Zapisovat UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Udává, kolik značek má být přeskočeno před vykreslením další. Použito pro osy kategorií nebo sérií. Číst/Zapisovat UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Získá název osy. Pouze ke čtení [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Udává vlastní hodnotu podtečného koše. Použito, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true. |

## Metody

| Název | Popis |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Nastaví vlastnost IAxis.CategoryAxisType hodnotou, která je automaticky určena na základě dat osy. |

### Viz také

* třída [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* třída [AxesManager](../axesmanager)
* rozhraní [IAxis](../iaxis)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->