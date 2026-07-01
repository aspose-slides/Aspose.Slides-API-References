---
title: ChartSeriesGroup
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en grupp av serier.
type: docs
weight: 1440
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
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Anger hur bubbelstorleksvärdena representeras i bubbeldiagrammet. Läs/skriv [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Läs/skriv Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Returnerar diagrammets förälder. Läs-endast [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Anger storleken på hålet i ett donutsdiagram (kan vara mellan 0 och 90 procent av storleken på plotområdet). Läs/skriv Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Hämtar eller anger vinkeln på den första biten i ett paj- eller donutsdiagram, i grader (medurs från toppen, från 0 till 360 grader). Läs/skriv UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Returnerar eller anger avståndet, som en procentsats av markörbredden, mellan dataserierna i ett 3D-diagram. Läs/skriv UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Anger avståndet mellan stapel- eller kolumnkluster, som en procentsats av stapel- eller kolumnbredden. Läs/skriv UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Sant om diagrammet har serielinjer. Tillämpas på staplade staplar och OfPie-diagram. Läs/skriv Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Anger HiLowLines-format. HiLowLines tillämpas med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose diagramtyper. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Anger att varje datamarkör i serien har en annan färg. Läs/skriv Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Hämtar elementet på det angivna indexet. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procentsats (från -100% till 100%). - -100%: Maximalt avstånd (staplar är helt separerade). - 0%: Staplar placeras sida vid sida utan överlappning eller avstånd. - 100%: Maximal överlappning (staplar överlappar varandra helt). Denna egenskap är läs/skriv SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. Läs/skriv [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Den anpassade delningsinformationen för ett paj-i-paj- eller stapel-i-paj-diagram med en anpassad delning. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. Läs-endast [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. Används tillsammans med egenskapen PieSplitBy. Läs/skriv Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indikerar om serier i denna grupp ritas på sekundär axel. Läs-endast Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Anger storleken på den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram, som en procentsats av storleken på den första pajen (kan vara mellan 5 och 200 procent). Läs/skriv UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Returnerar en samling av serier. Läs-endast [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Returnerar en typ av denna seriegroupp. Läs-endast [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Tillhandahåller åtkomst till upp/ner-staplar i linje- eller börsdiagram. Läs-endast [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Anmärkningar

1) Se sammanfattning och anmärkningar för ChartSeriesGroupCollection klass och CombinableSeriesTypesGroup enum.  
2) Grupp av serier innehåller vissa seriegenskaper som är gemensamma för varje serie i gruppen ("series group properties"). "Series group properties" i ChartSeriesGroup klass är läs/skriv. Varje av "series group properties" kan ha en läs-endast projicering i ChartSeries klass.

### Se även

* gränssnitt [IChartSeriesGroup](../ichartseriesgroup)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->