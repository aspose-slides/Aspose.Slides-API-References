---
title: IChartSeries
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje sérii grafu.
type: docs
weight: 1950
url: /cs/aspose.slides.charts/ichartseries/
---
## IChartSeries rozhraní

Reprezentuje sérii grafu.

```csharp
public interface IChartSeries : IChartComponent
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Umožňuje získat základní rozhraní IChartComponent. Pouze pro čtení [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Určuje tvar série 3-D sloupcového grafu. Změna hodnoty této vlastnosti může způsobit automatickou změnu typu série. Čtení/Zápis [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Určuje, jak jsou hodnoty velikosti bublin zobrazeny v bublinovém grafu. Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.BubbleSizeRepresentation pro čtení/zápis k změně hodnoty. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Určuje škálovací faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.BubbleSizeScale pro čtení/zápis k změně hodnoty. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Vrací kolekci datových bodů této série. Pouze pro čtení [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Určuje velikost otvoru v prstencovém grafu (může být mezi 10 a 90 procenty velikosti vykreslovací oblasti). Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.DoughnutHoleSize pro čtení/zápis k změně hodnoty. Pouze pro čtení Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Reprezentuje ErrorBars série s osou X. ErrorBars se směrem X jsou k dispozici pro série typu area, bar, scatter a bubble. Pro jakékoli jiné typy grafu tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k zadání hodnoty (s vlastností [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Pouze pro čtení [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Reprezentuje ErrorBars série s osou Y. ErrorBars se směrem Y jsou k dispozici pro série typu area, bar, line, scatter a bubble. Pro jakékoli jiné typy grafu tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k zadání hodnoty (s vlastností [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Pouze pro čtení [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Vzdálenost otevřeného výseče koláče od středu koláčového grafu je vyjádřena jako procento průměru koláče. Čtení/Zápis Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Určuje úhel první výseče koláče nebo prstence v odstínech (ve směru hodinových ručiček odshora, od 0 do 360 stupňů). Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.FirstSliceAngle pro čtení/zápis k změně hodnoty. Pouze pro čtení UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Vrací formát série. Pouze pro čtení [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Vrací nebo nastavuje vzdálenost, jako procento šířky značky, mezi datovými sériemi ve 3D grafu. Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.GapDepth pro čtení/zápis k změně hodnoty. Pouze pro čtení Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Určuje prostor mezi shluky sloupců nebo pruhů jako procento šířky sloupce nebo pruhu. Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.GapWidth pro čtení/zápis k změně hodnoty. Pouze pro čtení Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Určuje, zda jsou pro tuto sérii a související série přítomny čáry sérií. Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.HasSeriesLines pro čtení/zápis k změně hodnoty. Použijte vlastnost ParentSeriesGroup.SeriesLinesFormat pro formát čar sérií. Pouze pro čtení Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Určuje, zda má čárový nebo akciový graf svislé/sloupové pásky nahoru/dolů. Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.UpDownBars.HasUpDownBars pro čtení/zápis k změně hodnoty. Použijte vlastnost ParentSeriesGroup.UpDownBars pro formát svislých/pasových pruhů. Pouze pro čtení Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Určuje invertovanou plnou barvu pro sérii. Pro aplikaci nastavení barvy nastavte formát série FillType na FillType.Solid. Čtení/Zápis [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Určuje, že série sloupců, pruhů nebo bublin invertuje barvy, pokud je hodnota záporná. Čtení/Zápis Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Určuje, že každý datový marker v sérii má jinou barvu. Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.IsColorVaried pro čtení/zápis k změně hodnoty. Pouze pro čtení Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Vrací štítky série. Pouze pro čtení [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Vrací značku série. Pouze pro čtení [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Vrací název série. Pouze pro čtení [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Vrací nebo nastavuje číselný formát pro velikosti bublin série. Čtení/Zápis String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Vrací nebo nastavuje číselný formát pro hodnoty série. Čtení/Zápis String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Vrací nebo nastavuje číselný formát pro hodnoty x série. Čtení/Zápis String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Vrací nebo nastavuje číselný formát pro hodnoty y série. Čtení/Zápis String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Vrací pořadí série. Čtení/Zápis Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Určuje, jak moc se sloupce a pruhy překrývají v 2-D grafech, jako procento (od -100 % do 100 %). Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií. Jedná se o projekci příslušné vlastnosti v nadřazené skupině sérií, a tak je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte vlastnost ParentSeriesGroup.Overlap pro čtení/zápis. Pouze pro čtení SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Reprezentuje rozvržení štítků nadřazené kategorie. Používá se pouze u grafů Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Vrací nadřazenou skupinu sérií. Pouze pro čtení [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Určuje, jak určit, které datové body jsou ve druhém koláči nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.PieSplitBy pro čtení/zápis k změně hodnoty. Pouze pro čtení [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které se mají vykreslit ve druhém koláči nebo sloupci. Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Pouze pro čtení [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Určuje hodnotu, která se použije pro určení, které datové body jsou ve druhém koláči nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Používá se společně s vlastností PieSplitBy. Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.PieSplitPosition pro čtení/zápis k změně hodnoty. Pouze pro čtení Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Udává, zda je tato série vykreslena na druhé hodnotové ose. Čtení/Zápis Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Reprezentuje metodu kvartilu. Používá se pouze u grafů BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Reprezentuje položku legendy související s touto sérií. Pouze pro čtení [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Určuje velikost druhého koláče nebo sloupce v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 a 200 procenty). Tato vlastnost není jen této sérii, ale všem sériím nadřazené skupiny sérií – jedná se o projekci příslušné skupinové vlastnosti. Tato vlastnost je tedy pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost ParentSeriesGroup.SecondPieSize pro čtení/zápis k změně hodnoty. Pouze pro čtení UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Reprezentuje spojnicové čáry. Používá se pouze u grafů Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Reprezentuje vnitřní body. True, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Používá se pouze u grafů BoxAndWhisker. Čtení/Zápis Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Reprezentuje průměrné značky. True, pokud je průměrná čára zobrazena v grafu BoxAndWhisker. Používá se pouze u grafů BoxAndWhisker. Čtení/Zápis Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Reprezentuje průměrné značky. True, pokud jsou průměrné značky zobrazeny v grafu BoxAndWhisker. Používá se pouze u grafů BoxAndWhisker. Čtení/Zápis Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Reprezentuje odlehlé body. True, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Používá se pouze u grafů BoxAndWhisker. Čtení/Zápis Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Reprezentuje vyhlazení křivky. True, pokud je vyhlazení křivky zapnuto pro čárový nebo rozptýlený graf. Používá se pouze u čárových a rozptýlených grafů spojených čarami. Čtení/Zápis Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Kolekce trendových čar série. Pouze pro čtení [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Vrací typ této série. Čtení/Zápis [`ChartType`](../charttype). |

## Metody

| Název | Popis |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Vrací automatickou barvu série na základě indexu série a stylu grafu. Tato barva se používá jako výchozí, pokud je FillType nastaven na NotDefined. |

### Viz také

* rozhraní [IChartComponent](../ichartcomponent)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->