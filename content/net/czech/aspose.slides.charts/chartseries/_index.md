---
title: ChartSeries
second_title: Aspose.Sildes pro .NET referenční příručka API
description: Zastupuje řadu grafu.
type: docs
weight: 1440
url: /cs/aspose.slides.charts/chartseries/
---
## ChartSeries třída

Represents a chart series.

```csharp
public class ChartSeries : IChartSeries
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Určuje tvar řady 3-D sloupcového grafu. Změna hodnoty této vlastnosti může automaticky změnit typ řady. Čtení/Zápis [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bublinovém grafu. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci odpovídající vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.BubbleSizeRepresentation (čtení/zápis). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 % výchozí velikosti). Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci odpovídající vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.BubbleSizeScale (čtení/zápis). |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Vrací nadřazený graf. Pouze pro čtení [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Vrací kolekci datových bodů této řady. Pouze pro čtení [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Určuje velikost díry v prstencovém grafu (může být mezi 10 a 90 % velikosti oblasti vykreslování). Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci odpovídající vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.DoughnutHoleSize (čtení/zápis). Pouze pro čtení Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Reprezentuje ErrorBars řady se směrem X. ErrorBars se směrem X jsou k dispozici pro řady typu area, bar, scatter a bubble. Pro ostatní typy grafů tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints pro určení hodnoty (s vlastností [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Pouze pro čtení [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Reprezentuje ErrorBars řady se směrem Y. ErrorBars se směrem Y jsou k dispozici pro řady typu area, bar, line, scatter a bubble. Pro ostatní typy grafů tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints pro určení hodnoty (s vlastností [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Pouze pro čtení [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Vzdálenost otevřeného výseku koláče od středu koláčového grafu je vyjádřena jako procento průměru koláče. Čtení/Zápis Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Určuje úhel prvního výseku koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci odpovídající vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.FirstSliceAngle (čtení/zápis). Pouze pro čtení UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Vrací formát řady. Pouze pro čtení [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Vrací nebo nastavuje vzdálenost, jako procento šířky značky, mezi datovými řadami ve 3D grafu. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad. Jedná se o projekci odpovídající vlastnosti v nadřazené skupině řad, a proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.GapDepth (čtení/zápis). Pouze pro čtení Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Určuje mezeru mezi shluky sloupců nebo pruhů jako procento šířky sloupce či pruhu. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad. Jedná se o projekci odpovídající vlastnosti v nadřazené skupině řad, a proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.GapWidth (čtení/zápis). Pouze pro čtení Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Určuje, zda existují řadové čáry pro tuto řadu a související řady. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad. Jedná se o projekci odpovídající vlastnosti v nadřazené skupině řad, a proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.HasSeriesLines (čtení/zápis). Pro formát řadových čar použijte vlastnost ParentSeriesGroup.SeriesLinesFormat. Pouze pro čtení Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Určuje, zda má Line- nebo Stock-graf horní/dolní pruhy. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad. Jedná se o projekci odpovídající vlastnosti v nadřazené skupině řad, a proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.UpDownBars.HasUpDownBars (čtení/zápis). Pro formát horních/dolních pruhů použijte vlastnost ParentSeriesGroup.UpDownBars. Pouze pro čtení Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Určuje inverzní plnou barvu pro řadu. Pro použití nastavení barvy nastavte formát řady FillType na FillType.Solid. Čtení/Zápis [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Určuje, že sloupcová, sloupcová nebo bublinová řada invertuje své barvy, pokud je hodnota záporná. Čtení/Zápis Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Určuje, že každý datový marker v řadě má jinou barvu. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad. Jedná se o projekci odpovídající vlastnosti v nadřazené skupině řad, a proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.IsColorVaried (čtení/zápis). Pouze pro čtení Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Vrací štítky řady. Pouze pro čtení [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Značka. Pouze pro čtení [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Vrací název řady. Pouze pro čtení [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Čtení/Zápis String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Čtení/Zápis String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Čtení/Zápis String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Čtení/Zápis String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Vrací pořadí řady. Čtení/Zápis Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Určuje, jak moc se sloupce a pruhy překrývají v 2-D grafech, jako procento (od -100 % do 100 %). Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad. Jedná se o projekci odpovídající vlastnosti v nadřazené skupině řad, a proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte vlastnost !:ParentSeriesGroup.Overlap (čtení/zápis). Pouze pro čtení SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Representuje rozvržení štítků nadřazené kategorie. Používá se jen pro grafy Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Pouze pro čtení [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Určuje, jak určit, které datové body jsou ve druhém výseku nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci odpovídající vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.PieSplitBy (čtení/zápis). Pouze pro čtení [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém výseku nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci odpovídající vlastnosti skupiny. Pouze pro čtení [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém výseku nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci odpovídající vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.PieSplitPosition (čtení/zápis). Pouze pro čtení Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Indikuje, zda je tato řada vykreslena na sekundární ose. Čtení/Zápis Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Representuje metodu kvartilu. Používá se jen pro grafy BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Representuje položku legendy související s touto řadou. Pouze pro čtení [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Určuje velikost druhého výseku nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního výseku (může být mezi 5 a 200 %). Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci odpovídající vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.SecondPieSize (čtení/zápis). Pouze pro čtení UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Representuje spojovací čáry. Používá se jen pro grafy Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Representuje vnitřní body. True, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Používá se jen pro grafy BoxAndWhisker. Čtení/Zápis Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Representuje průměrnou čáru. True, pokud jsou průměrné čáry zobrazeny v grafu BoxAndWhisker. Používá se jen pro grafy BoxAndWhisker. Čtení/Zápis Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Representuje průměrné značky. True, pokud jsou průměrné značky zobrazeny v grafu BoxAndWhisker. Používá se jen pro grafy BoxAndWhisker. Čtení/Zápis Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Representuje odlehlé body. True, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Používá se jen pro grafy BoxAndWhisker. Čtení/Zápis Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Representuje vyhlazování křivky. True, pokud je vyhlazování křivky zapnuto pro spojnicový nebo bodový graf. Používá se jen pro spojnicové a bodové grafy propojené čarami. Čtení/Zápis Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Kolekce trendových čar řady. Pouze pro čtení [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Vrací typ této řady. Čtení/Zápis [`ChartType`](../charttype). |

## Metody

| Název | Popis |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Vrací automatickou barvu řady na základě indexu řady a stylu grafu. Tato barva se používá jako výchozí, pokud je FillType rovno NotDefined. |

### Viz také

* rozhraní [IChartSeries](../ichartseries)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->