---
title: IChartSeriesGroup
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en grupp av serier.
type: docs
weight: 1930
url: /sv/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup gränssnitt

Representerar en grupp av serier.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Gör det möjligt att hämta bas-IChartComponent-gränssnittet. Skrivskyddad [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Anger hur bubbelstorleksvärdena representeras i bubbeldiagrammet. Läs/skriv [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Anger skalningsfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Läs/skriv Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Anger storleken på hålet i ett munkdiagram (kan vara mellan 10 och 90 procent av plottområdets storlek). Läs/skriv Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Hämtar eller anger vinkeln på det första sektorsegmentet i ett paj- eller munkdiagram, i grader (medurs från toppen, från 0 till 360 grader). Läs/skriv UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Returnerar eller anger avståndet, som procent av markörens bredd, mellan dataserierna i ett 3D-diagram. Läs/skriv UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Anger mellanrummet mellan stapel- eller kolumnkluster, som procent av stapel- eller kolumnbredden. Läs/skriv UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Sant om diagrammet har serielinjer. Tillämpligt på staplade stapeldiagram och OfPie-diagram. Läs/skriv Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Anger HiLowLines-format. HiLowLines tillämpas med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose diagramtyper. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Anger att varje datamarkör i serien har en annan färg. Läs/skriv Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Hämtar elementet på det angivna indexet. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som procent (från -100 % till 100 %). - -100 %: Maximal distans (staplarna är helt separerade). - 0 %: Staplarna placeras bredvid varandra utan överlappning eller avstånd. - 100 %: Maximal överlappning (staplarna överlappar varandra helt). Denna egenskap är läs/skriv SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. Läs/skriv [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Den anpassade uppdelningsinformationen för ett paj-av-paj- eller stapel-av-paj-diagram med en anpassad uppdelning. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. Skrivskyddad [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Anger ett värde som ska användas för att bestämma vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram. Används tillsammans med egenskapen PieSplitBy. Läs/skriv Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Indikerar om serier i den här gruppen plottas på sekundär axel. Skrivskyddad Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Anger storleken på den andra pajen eller stapeln i ett paj-av-paj- eller stapel-av-paj-diagram, som procent av den första pajens storlek (kan vara mellan 5 och 200 procent). Läs/skriv UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Returnerar en skrivskyddad samling av diagramserier. Skrivskyddad [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Returnerar en typ av den här serieggruppen. Skrivskyddad [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Tillhandahåller åtkomst till upp/ner staplar i linje- eller aktiediagram. Skrivskyddad [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Anmärkningar

1) Se sammanfattning och anmärkningar för ChartSeriesGroupCollection klass och CombinableSeriesTypesGroup enum. 2) Grupp av serier innehåller vissa seriegenskaper som är gemensamma för varje serie i gruppen ("seriegroupegenskaper"). "Seriegroupegenskaper" i ChartSeriesGroup klass är läs/skriv. Varje av "seriegroupegenskaper" kan ha en skrivskyddad projektion i ChartSeries klass.

### Se även

* gränssnitt [IChartComponent](../ichartcomponent)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->