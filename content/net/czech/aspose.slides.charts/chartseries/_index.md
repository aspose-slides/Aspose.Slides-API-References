---
title: ChartSeries
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje sérii grafu.
type: docs
weight: 1450
url: /cs/aspose.slides.charts/chartseries/
---
## ChartSeries třída

Reprezentuje sérii grafu.

```csharp
public class ChartSeries : IChartSeries
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Určuje tvar série ve 3-D sloupcovém grafu. Změna hodnoty této vlastnosti může způsobit automatickou změnu typu série. Číst/Zapisovat [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bublinovém grafu. Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.BubbleSizeRepresentation s možností čtení a zápisu pro změnu hodnoty. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 % a 300 % výchozí velikosti). Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.BubbleSizeScale s možností čtení a zápisu pro změnu hodnoty. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Vrací nadřazený graf. Pouze pro čtení [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Vrací kolekci datových bodů této série. Pouze pro čtení [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Určuje velikost otvoru v prstencovém grafu (může být mezi 10 % a 90 % velikosti vykreslovací plochy). Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.DoughnutHoleSize s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Reprezentuje ErrorBars série se směrem X. ErrorBars se směrem X jsou k dispozici pro série typů area, bar, scatter a bubble. Pro všechny ostatní typy grafů tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints pro určení hodnoty (s vlastností [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Pouze pro čtení [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Reprezentuje ErrorBars série se směrem Y. ErrorBars se směrem Y jsou k dispozici pro série typů area, bar, line, scatter a bubble. Pro všechny ostatní typy grafů tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints pro určení hodnoty (s vlastností [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Pouze pro čtení [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Vzdálenost otevřené výseč koláčového grafu od středu koláčového grafu je vyjádřena v procentech průměru koláče. Číst/Zapisovat Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Určuje úhel první výseče koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od vrchu, od 0 do 360°). Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.FirstSliceAngle s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Vrací formát série. Pouze pro čtení [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Vrací nebo nastavuje vzdálenost, jako procento šířky značky, mezi datovými sériemi ve 3D grafu. Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.GapDepth s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Určuje prostor mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.GapWidth s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Určuje, zda existují čáry série pro tuto sérii a související série. Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.HasSeriesLines s možností čtení a zápisu pro změnu hodnoty. Použijte vlastnost ParentSeriesGroup.SeriesLinesFormat pro formát čar série. Pouze pro čtení Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Určuje, zda má čárový nebo akciový graf svislé pruhy nahoru/dolu. Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.UpDownBars.HasUpDownBars s možností čtení a zápisu pro změnu hodnoty. Použijte vlastnost ParentSeriesGroup.UpDownBars pro formát svislých pruhů. Pouze pro čtení Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Určuje invertovanou plnou barvu pro sérii. Pro aplikaci nastavení barvy nastavte ve formátu série FillType na FillType.Solid. Číst/Zapisovat [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Určuje, že sloupcová, sloupcová nebo bublinová série invertuje své barvy, pokud je hodnota záporná. Číst/Zapisovat Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Určuje, že každý datový značkový bod v sérii má jinou barvu. Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.IsColorVaried s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Vrací štítky série. Pouze pro čtení [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Značka. Pouze pro čtení [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Vrací název série. Pouze pro čtení [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Číst/Zapisovat String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Číst/Zapisovat String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Číst/Zapisovat String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Číst/Zapisovat String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Vrací pořadí série. Číst/Zapisovat Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Určuje, jak moc se překrývají sloupce a pruhy v 2-D grafech, jako procento (od -100 % do 100 %). Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Pro změnu hodnoty použijte !:ParentSeriesGroup.Overlap s možností čtení a zápisu. Pouze pro čtení SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Reprezentuje rozložení štítků nadřazených kategorií. Použitelné jen pro grafy Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Pouze pro čtení [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.PieSplitBy s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém koláči nebo pruhu. Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Pouze pro čtení [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.PieSplitPosition s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Indikuje, zda je tato série vykreslena na sekundární ose. Číst/Zapisovat Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Reprezentuje metodu kvartilu. Použitelná jen pro grafy BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Reprezentuje položku legendy související s touto sérií. Pouze pro čtení [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Určuje velikost druhého koláče nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 % a 200 %). Tato vlastnost se vztahuje nejen na tuto sérii, ale i na všechny série nadřazené skupiny sérií – je projekcí odpovídající skupinové vlastnosti. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.SecondPieSize s možností čtení a zápisu pro změnu hodnoty. Pouze pro čtení UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Reprezentuje spojovací čáry. Použitelné jen pro grafy Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Reprezentuje vnitřní body. True, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Použitelné jen pro grafy BoxAndWhisker. Číst/Zapisovat Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Reprezentuje čáru průměru. True, pokud je čára průměru zobrazena v grafu BoxAndWhisker. Použitelné jen pro grafy BoxAndWhisker. Číst/Zapisovat Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Reprezentuje značky průměru. True, pokud jsou značky průměru zobrazeny v grafu BoxAndWhisker. Použitelné jen pro grafy BoxAndWhisker. Číst/Zapisovat Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Reprezentuje odlehlé body. True, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Použitelné jen pro grafy BoxAndWhisker. Číst/Zapisovat Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Reprezentuje vyhlazení křivky. True, pokud je vyhlazení křivky zapnuto pro čárový graf nebo bodový graf. Použitelné jen pro spojované čárové a bodové grafy. Číst/Zapisovat Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Kolekce trendových čar série. Pouze pro čtení [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Vrací typ této série. Číst/Zapisovat [`ChartType`](../charttype). |

## Metody

| Název | Popis |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Vrací automatickou barvu série založenou na indexu série a stylu grafu. Tato barva se používá jako výchozí, pokud je FillType nastaven na NotDefined. |

### Viz také

* rozhraní [IChartSeries](../ichartseries)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->