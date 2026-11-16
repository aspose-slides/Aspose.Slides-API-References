---
title: ChartSeriesGroup
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en grupp av serier.
type: docs
weight: 1470
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
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Anger skalningsfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Läs/skriv Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Returnerar föräldradiagrammet. Endast läsning [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Anger storleken på hålet i ett donutdiagram (kan vara mellan 0 och 90 procent av plotområdets storlek). Läs/skriv Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Hämtar eller anger vinkeln på den första paj- eller donutdiagrammets del, i grader (medurs från toppen, från 0 till 360 grader). Läs/skriv UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Hämtar eller anger avståndet mellan dataserier i ett 3D-diagram, som en procent av markörens bredd. Värdet måste vara mellan 0 och 500. Läs/skriv UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Hämtar eller anger avståndet mellan stapel- eller kolumnkluster, som en procent av stapelns eller kolumnens bredd. Värdet måste vara mellan 0 och 500. Läs/skriv UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Sant om diagrammet har serielinjer. Tillämpas på staplade stapeldiagram och OfPie-diagram. Läs/skriv Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Anger HiLowLines-format. HiLowLines tillämpas med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose diagramtyper. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Anger att varje datamarkör i serien har en annan färg. Läs/skriv Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Hämtar elementet på det angivna indexet. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som en procent (från -100 % till 100 %). - -100 %: Maximal avstånd (staplarna är helt separerade). - 0 %: Staplarna placeras sida vid sida utan överlappning eller avstånd. - 100 %: Maximal överlappning (staplarna helt överlappar varandra). Denna egenskap är läs/skriv SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Läs/skriv [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Den anpassade split-informationen för ett pie-of-pie- eller bar-of-pie-diagram med en anpassad split. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Endast läsning [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med egenskapen PieSplitBy. Läs/skriv Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Indikerar om serier i denna grupp plottas på sekundär axel. Endast läsning Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Anger storleken på den andra pajen eller stapeln i ett pie-of-pie-diagram eller ett bar-of-pie-diagram, som en procent av storleken på den första pajen (kan vara mellan 5 och 200 procent). Läs/skriv UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Returnerar en samling av serier. Endast läsning [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Returnerar en typ av den här serieggruppen. Endast läsning [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Tillhandahåller åtkomst till upp/ner-staplar i linje- eller aktiediagram. Endast läsning [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Anmärkningar

1) Se sammanfattning och anmärkningar för ChartSeriesGroupCollection-klassen och CombinableSeriesTypesGroup-enumerationen. 2) Grupp av serier innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen (“series group properties”). “Series group properties” i ChartSeriesGroup-klassen är läs/skriv. Varje “series group properties” kan ha en endast-läslig projektion i ChartSeries-klassen.

### Se även

* gränssnitt [IChartSeriesGroup](../ichartseriesgroup)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->