---
title: ChartSeries
second_title: Aspose.Sildes pro .NET – reference API
description: Reprezentuje řadu grafu.
type: docs
weight: 1420
url: /cs/aspose.slides.charts/chartseries/
---
## ChartSeries třída

Představuje řadu grafu.

```csharp
public class ChartSeries : IChartSeries
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Určuje tvar řady 3-D sloupcového grafu. Změna hodnoty této vlastnosti může automaticky změnit typ řady. Čtení/zápis [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bublinovém grafu. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.BubbleSizeRepresentation pro čtení/zápis a změnu hodnoty. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Určuje měřítko pro bublinový graf (může být mezi 0 a 300 % výchozí velikosti). Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.BubbleSizeScale pro čtení/zápis a změnu hodnoty. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Vrací nadřazený graf. Pouze pro čtení [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Vrací kolekci datových bodů této řady. Pouze pro čtení [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Určuje velikost díry v prstencovém grafu (může být mezi 10 a 90 % velikosti oblasti vykreslování). Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.DoughnutHoleSize pro čtení/zápis a změnu hodnoty. Pouze pro čtení Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Reprezentuje ErrorBars řady se směrem X. ErrorBars se směrem X jsou dostupné pro řady typu area, bar, scatter a bubble. Pro ostatní typy grafů tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Pouze pro čtení [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Reprezentuje ErrorBars řady se směrem Y. ErrorBars se směrem Y jsou dostupné pro řady typu area, bar, line, scatter a bubble. Pro ostatní typy grafů tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Pouze pro čtení [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Vzdálenost otevřeného výseku koláče od středu koláčového grafu je vyjádřena v procentech průměru koláče. Čtení/zápis Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Určuje úhel prvního výseku koláče nebo prstence, ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.FirstSliceAngle pro čtení/zápis a změnu hodnoty. Pouze pro čtení UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Vrací formát řady. Pouze pro čtení [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Vrací nebo nastavuje vzdálenost, jako procento šířky značky, mezi datovými řadami ve 3D grafu. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.GapDepth pro čtení/zápis a změnu hodnoty. Pouze pro čtení Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Určuje prostor mezi shluky sloupců nebo pruhů, jako procento šířky sloupce nebo pruhu. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.GapWidth pro čtení/zápis a změnu hodnoty. Pouze pro čtení Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Určuje, zda existují čáry řady pro tuto řadu a související řady. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.HasSeriesLines pro čtení/zápis a změnu hodnoty. Použijte vlastnost ParentSeriesGroup.SeriesLinesFormat pro formát čar řady. Pouze pro čtení Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Určuje, zda má graf Line nebo Stock svislé/sloupové pruhy nahoru/dolů. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.UpDownBars.HasUpDownBars pro čtení/zápis a změnu hodnoty. Použijte vlastnost ParentSeriesGroup.UpDownBars pro formát svislých/pruhových čar. Pouze pro čtení Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Určuje invertovanou plnou barvu pro řadu. Pro použití nastavení barvy nastavte formát řady FillType na FillType.Solid. Čtení/zápis [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Určuje, zda má sloupcová, sloupcová nebo bublinová řada invertovat barvy, pokud je hodnota záporná. Čtení/zápis Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Určuje, že každý datový marker v řadě má jinou barvu. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.IsColorVaried pro čtení/zápis a změnu hodnoty. Pouze pro čtení Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Vrací štítky řady. Pouze pro čtení [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Značka. Pouze pro čtení [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Vrací název řady. Pouze pro čtení [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Čtení/zápis String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Čtení/zápis String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Čtení/zápis String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Čtení/zápis String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Vrací pořadí řady. Čtení/zápis Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Určuje, jak moc se sloupce a sloupce překrývají v 2-D grafech, jako procento (od -100 % do 100 %). Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad. Jedná se o projekci příslušné vlastnosti v nadřazené skupině řad, a proto je tato vlastnost pouze pro čtení. Pro změnu použijte vlastnost ParentSeriesGroup.Overlap pro čtení/zápis. Pouze pro čtení SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Reprezentuje rozložení štítků nadřazené kategorie. Používá se pouze u grafů Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Pouze pro čtení [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Určuje, jak určit, které datové body jsou ve druhém výseku koláče nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.PieSplitBy pro čtení/zápis a změnu hodnoty. Pouze pro čtení [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Vlastní rozdělovací informace pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém výseku nebo pruhu. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Pouze pro čtení [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Určuje hodnotu, která má být použita k určení, které datové body jsou ve druhém výseku koláče nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.PieSplitPosition pro čtení/zápis a změnu hodnoty. Pouze pro čtení Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Udává, zda je tato řada vykreslena na sekundární ose. Čtení/zápis Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Reprezentuje metodu kvartilu. Používá se pouze u grafů BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Reprezentuje legendový záznam související s touto řadou. Pouze pro čtení [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Určuje velikost druhého výseku nebo pruhu v grafu pie-of-pie či bar-of-pie, jako procento velikosti prvního výseku (může být mezi 5 a 200 %). Tato vlastnost platí nejen pro tuto řadu, ale i pro všechny řady nadřazené skupiny řad – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.SecondPieSize pro čtení/zápis a změnu hodnoty. Pouze pro čtení UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Reprezentuje spojovací čáry. Používá se pouze u grafů Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Reprezentuje vnitřní body. True, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Používá se pouze u grafů BoxAndWhisker. Čtení/zápis Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Reprezentuje čáru průměru. True, pokud je čára průměru zobrazena v grafu BoxAndWhisker. Používá se pouze u grafů BoxAndWhisker. Čtení/zápis Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Reprezentuje značky průměru. True, pokud jsou značky průměru zobrazeny v grafu BoxAndWhisker. Používá se pouze u grafů BoxAndWhisker. Čtení/zápis Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Reprezentuje odlehlé body. True, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Používá se pouze u grafů BoxAndWhisker. Čtení/zápis Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Reprezentuje vyhlazení křivky. True, pokud je vyhlazení křivky zapnuto pro čárový nebo bodový graf spojený čarami. Používá se pouze u čárových a bodových grafů spojených čarami. Čtení/zápis Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Kolekce trendových čar řad. Pouze pro čtení [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Vrací typ této řady. Čtení/zápis [`ChartType`](../charttype). |

## Metody

| Název | Popis |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Vrací automatickou barvu řady na základě indexu řady a stylu grafu. Tato barva je použita jako výchozí, pokud je FillType nastaveno na NotDefined. |

### Viz také

* rozhraní [IChartSeries](../ichartseries)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->