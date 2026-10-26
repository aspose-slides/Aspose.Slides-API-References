---
title: IChartSeries
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje řadu grafu.
type: docs
weight: 1930
url: /cs/aspose.slides.charts/ichartseries/
---
## IChartSeries rozhraní

Reprezentuje řadu v grafu.

```csharp
public interface IChartSeries : IChartComponent
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Umožňuje získat základní rozhraní IChartComponent. Pouze pro čtení [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Určuje tvar řady ve 3-D sloupcovém grafu. Změna hodnoty této vlastnosti může automaticky změnit typ řady. Čtení/Zápis [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bublinovém grafu. Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.BubbleSizeRepresentation s čtením/zápisem pro změnu hodnoty. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.BubbleSizeScale s čtením/zápisem pro změnu hodnoty. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Vrací kolekci datových bodů této řady. Pouze pro čtení [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Určuje velikost otvoru v prstencovém grafu (může být mezi 10 a 90 procenty velikosti vykreslovací plochy). Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.DoughnutHoleSize s čtením/zápisem pro změnu hodnoty. Pouze pro čtení Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Zastupuje chybové pruhy řady se směrem X. Chybové pruhy se směrem X jsou k dispozici pro řady typu oblast, sloupec, rozptyl a bublina. U všech ostatních typů grafů tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Pouze pro čtení [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Zastupuje chybové pruhy řady se směrem Y. Chybové pruhy se směrem Y jsou k dispozici pro řady typu oblast, sloupec, čára, rozptyl a bublina. U všech ostatních typů grafů tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Pouze pro čtení [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Vzdálenost otevřeného výseku koláče od středu koláčového grafu je vyjádřena jako procento průměru koláče. Čtení/Zápis Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Určuje úhel prvního výseku koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.FirstSliceAngle s čtením/zápisem pro změnu hodnoty. Pouze pro čtení UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Vrací formát řady. Pouze pro čtení [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Vrací nebo nastaví vzdálenost, jako procento šířky značky, mezi datovými řadami v 3D grafu. Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.GapDepth s čtením/zápisem pro změnu hodnoty. Pouze pro čtení Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Určuje mezeru mezi shluky sloupců nebo sloupcových skupin, jako procento šířky sloupce nebo sloupce. Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.GapWidth s čtením/zápisem pro změnu hodnoty. Pouze pro čtení Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Určuje, zda existují čáry řad pro tuto řadu a související řady. Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.HasSeriesLines s čtením/zápisem pro změnu hodnoty. Použijte vlastnost ParentSeriesGroup.SeriesLinesFormat pro formát čar řad. Pouze pro čtení Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Určuje, zda má čárový nebo akciový graf svislé pruhy nahoru/dolů. Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.UpDownBars.HasUpDownBars s čtením/zápisem pro změnu hodnoty. Použijte vlastnost ParentSeriesGroup.UpDownBars pro formát svislých pruhů. Pouze pro čtení Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Určuje invertovanou plnou barvu pro řadu. Pro použití nastavení barvy nastavte FillType formátu řady na FillType.Solid. Čtení/Zápis [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Určuje, že sloupcová, sloupcová nebo bublinová řada invertuje své barvy, pokud je hodnota záporná. Čtení/Zápis Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Určuje, že každý datový marker v řadě má jinou barvu. Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.IsColorVaried s čtením/zápisem pro změnu hodnoty. Pouze pro čtení Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Vrací štítky řady. Pouze pro čtení [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Vrací marker řady. Pouze pro čtení [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Vrací název řady. Pouze pro čtení [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Vrací nebo nastaví formát čísel pro velikosti bublin řady. Čtení/Zápis String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Vrací nebo nastaví formát čísel pro hodnoty řady. Čtení/Zápis String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Vrací nebo nastaví formát čísel pro hodnoty x řady. Čtení/Zápis String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Vrací nebo nastaví formát čísel pro hodnoty y řady. Čtení/Zápis String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Vrací pořadí řady. Čtení/Zápis Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Určuje, jak moc se sloupce a sloupci překrývají v 2-D grafech, jako procento (od -100 % do 100 %). Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.Overlap s čtením/zápisem. Pouze pro čtení SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Zastupuje rozvržení štítků nadřazených kategorií. Použitelné pouze pro grafy Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Vrací nadřazenou skupinu řad. Pouze pro čtení [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Určuje, jak určit, které datové body jsou ve druhém výseku koláče nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.PieSplitBy s čtením/zápisem pro změnu hodnoty. Pouze pro čtení [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které se mají vykreslit ve druhém výseku nebo sloupci. Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Pouze pro čtení [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Určuje hodnotu, která se použije k určení, které datové body jsou ve druhém výseku koláče nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.PieSplitPosition s čtením/zápisem pro změnu hodnoty. Pouze pro čtení Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Indikuje, zda je tato řada vykreslena na druhé hodnotové ose. Čtení/Zápis Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Zastupuje metodu kvartilu. Použitelné pouze pro grafy BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Zastupuje položku legendy související s touto řadou. Pouze pro čtení [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Určuje velikost druhého výseku koláče nebo sloupce v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního výseku (může být mezi 5 a 200 procenty). Tato vlastnost není jen této řadě, ale všem řadám nadřazené skupiny řad – jde o projekci příslušné vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte vlastnost ParentSeriesGroup.SecondPieSize s čtením/zápisem pro změnu hodnoty. Pouze pro čtení UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Zastupuje spojovací čáry. Použitelné pouze pro grafy Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Zastupuje vnitřní body. Pravda, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/Zápis Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Zastupuje průměrné značky. Pravda, pokud je průměrná čára zobrazena v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/Zápis Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Zastupuje průměrné značky. Pravda, pokud jsou průměrné značky zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/Zápis Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Zastupuje odlehlé body. Pravda, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Použitelné pouze pro grafy BoxAndWhisker. Čtení/Zápis Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Zastupuje vyhlazování křivky. Pravda, pokud je vyhlazování křivky zapnuto pro čárový graf nebo rozptylový graf. Použitelné pouze pro čárové a rozptylové grafy spojené čarami. Čtení/Zápis Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Kolekce trendových čar řady. Pouze pro čtení [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Vrací typ této řady. Čtení/Zápis [`ChartType`](../charttype). |

## Metody

| Název | Popis |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Vrací automatickou barvu řady na základě indexu řady a stylu grafu. Tato barva je použita jako výchozí, pokud je FillType rovno NotDefined. |

### Viz také

* rozhraní [IChartComponent](../ichartcomponent)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->