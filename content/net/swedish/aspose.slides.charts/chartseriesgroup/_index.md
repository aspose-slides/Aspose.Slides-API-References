---
title: ChartSeriesGroup
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en grupp av serier.
type: docs
weight: 1460
url: /sv/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klass

Representerar en grupp av serier.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Anger hur bubbelstorleksvärden representeras i bubbeldiagrammet. Read/write [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Read/write Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Returnerar föräldrachart. Read-only [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Anger storleken på hålet i en donutdiagram (kan vara mellan 0 och 90 procent av plotområde). Read/write Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Hämtar eller anger vinkeln för den första paj- eller donutdiagramsegmentet, i grader (medurs från toppen, från 0 till 360 grader). Read/write UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Returnerar eller anger avståndet, som procent av markörbredden, mellan dataserier i ett 3D-diagram. Read/write UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Anger avståndet mellan stapel- eller kolumnkluster, som procent av stapel- eller kolumnbredden. Read/write UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Sant om diagrammet har serielinjer. Gäller för staplade staplar och OfPie-diagram. Read/write Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Anger HiLowLines-format. HiLowLines tillämpas med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose-diagramtyper. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Anger att varje datamarkör i serien har en annan färg. Read/write Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Hämtar elementet på angivet index. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som procent (från -100 % till 100 %). -100 %: Maximalt avstånd (staplarna är helt separerade). 0 %: Staplarna placeras sida-vid-sida utan överlappning eller avstånd. 100 %: Maximal överlappning (staplarna helt överlappar varandra). Denna egenskap är read/write SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Anger hur man bestämmer vilka datapunkter som ligger i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Read/write [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Den anpassade split-informationen för ett pie-of-pie- eller bar-of-pie-diagram med en anpassad split. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Read-only [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Anger ett värde som ska användas för att bestämma vilka datapunkter som ligger i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med PieSplitBy-egenskapen. Read/write Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Anger om serier i denna grupp ritas på sekundär axel. Read-only Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Anger storleken på den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram, som procent av storleken på den första pajen (kan vara mellan 5 och 200 procent). Read/write UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Returnerar en samling serier. Read-only [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Returnerar typen av denna serieguppe. Read-only [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Tillhandahåller åtkomst till upp/ner-staplar i linje- eller aktiediagram. Read-only [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Anmärkningar

1) Se sammanfattning och anmärkningar för ChartSeriesGroupCollection-klass och CombinableSeriesTypesGroup-enum. 2) Grupp av serier innehåller vissa serie-egenskaper som är gemensamma för varje serie i gruppen ("serie-grupp-egenskaper"). "Serie-grupp-egenskaper" i ChartSeriesGroup-klass är read/write. Varje av "serie-grupp-egenskaper" kan ha en read-only projektion i ChartSeries-klass.

### Se också

* interface [IChartSeriesGroup](../ichartseriesgroup)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->