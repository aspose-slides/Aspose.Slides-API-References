---
title: IAxis
second_title: Aspose.Sildes för .NET API-referens
description: Inkapslar objektet som representerar en diagramaxel.
type: docs
weight: 1710
url: /sv/aspose.slides.charts/iaxis/
---
## IAxis gränssnitt

Inkapslar objektet som representerar en diagramaxel.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Anger den faktiska huvudenheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Anger den faktiska skalningsfaktorn för huvudenheten på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Anger det faktiska maximala värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Anger den faktiska mindre enheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Anger den faktiska skalningsfaktorn för den mindre enheten på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Anger det faktiska minsta värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Representerar aggregeringstyp för kategoriaxel (gruppering). Tillämpas på kategori. Används endast med Histogram- eller HistogramPareto-serier. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Tillåter att hämta bas-gränssnittet IFormattedTextContainer. Skrivskyddad [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Anger om värdeaxeln korsar kategoriaxeln mellan kategorier. Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram. Läs/skriv Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Anger den minsta tidsenheten som representeras på datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Anger binbredd när egenskapen AggregationType är satt till AxisAggregationType.ByBinWidth. Tillämpas på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Anger typen av kategoriaxeln. Läs/skriv [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Representerar punkten på axeln där den vinkelräta axeln korsar den. Läs/skriv Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Representerar CrossType på den angivna axeln där den andra axeln korsar. Läs/skriv [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Anger skaleringsvärdet för visningsenheterna för värdeaxeln. Läs/skriv [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Representerar formatet för axeln. Skrivskyddad [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Bestämmer om en axel har en synlig titel. Läs/skriv Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indikerar om huvudvärdet för axeln tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indikerar om maximivärdet tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indikerar om den mindre enheten för axeln tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indikerar om minsta värdet tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Anger automatiskt overflow-bin-värde. Om falskt: använd egenskapen OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Anger automatiskt avstånd för tick-etiketter. Om falskt: använd egenskapen TickLabelSpacing. Läs/skriv Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Anger automatiskt avstånd för tick-markeringar. Om falskt: använd egenskapen TickMarksSpacing. Läs/skriv Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Anger automatiskt underflow-bin-värde. Om falskt: använd egenskapen UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Representerar om skalningstypen för värdeaxeln är logaritmisk eller ej. Läs/skriv Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indikerar om formatet är länkat till källdata. Läs/skriv Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Anger om overflow-bin tillämpas. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs/skriv Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Anger om underflow-bin tillämpas. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Representerar om axeln är synlig. Läs/skriv Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Anger avståndet för etiketter från axeln. Tillämpar på kategori- eller datumaxel. Värdet måste ligga mellan 0 % och 1000 %. Läs/skriv UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Representerar den logaritmiska basen. Standardvärdet är 10. Läs/skriv Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Representerar formatet för huvudnätlinjer på en diagramaxel. Skrivskyddad [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Representerar typen av huvud-tick-markering för den angivna axeln. Läs/skriv [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Representerar huvud-enheterna för datum- eller värdeaxel. Läs/skriv Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Representerar skalan för huvud-enheten på datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Representerar det maximala värdet på värdeaxeln. Läs/skriv Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Representerar formatet för mindre nätlinjer på en diagramaxel. Skrivskyddad [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Representerar typen av mindre tick-markering för den angivna axeln. Läs/skriv [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Representerar de mindre enheterna för datum- eller värdeaxel. Läs/skriv Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Representerar skalan för huvud-enheten på datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Representerar det minsta värdet på värdeaxeln. Läs/skriv Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Representerar formatsträngen för axel-etiketterna. Läs/skriv String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Anger antalet bin när egenskapen AggregationType är satt till AxisAggregationType.ByNumberOfBins. Tillämpas på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Anger anpassat overflow-bin-värde. Tillämpas när egenskapen IsAutomaticOverflowBin är falsk och egenskapen IsOverflowBin är sann. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Representerar axelns position. Läs/skriv [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Representerar om huvudnätlinjer visas. Skrivskyddad Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Representerar om mindre nätlinjer visas. Skrivskyddad Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Representerar positionen för tick-etikett-markeringar på den angivna axeln. Läs/skriv [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Representerar rotationsvinkeln för tick-etiketter. Läs/skriv Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Anger hur många tick-etiketter som ska hoppas över mellan etiketter som ritas. Läs/skriv UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Tillämpas på kategori- eller serieaxel. Läs/skriv UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Hämtar axelns titel. Skrivskyddad [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Anger anpassat underflow-bin-värde. Tillämpas när egenskapen IsAutomaticUnderflowBin är falsk och egenskapen IsUnderflowBin är sann. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Sätter IAxis.CategoryAxisType-egenskapen med ett värde som bestäms automatiskt utifrån axeldata. |

### Se också

* gränssnitt [IFormattedTextContainer](../iformattedtextcontainer)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->