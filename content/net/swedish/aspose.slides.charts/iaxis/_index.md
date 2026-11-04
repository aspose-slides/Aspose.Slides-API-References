---
title: IAxis
second_title: Aspose.Sildes för .NET API-referens
description: Inkapslar objektet som representerar en diagramaxel.
type: docs
weight: 1720
url: /sv/aspose.slides.charts/iaxis/
---
## IAxis gränssnitt

Inkapslar objektet som representerar ett diagramaxel.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Egenskaper

| Name | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Anger den faktiska huvudenheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Anger den faktiska skalan för huvudenheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Anger det faktiska maximala värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Anger den faktiska subenheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Anger den faktiska skalan för subenheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Anger det faktiska minimivärdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Representerar aggregeringstypen för kategoriaxeln (binning). Tillämpas på kategori. Används endast med Histogram- eller HistogramPareto-serier. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Tillåter att hämta den grundläggande IFormattedTextContainer-gränssnittet. Skrivskyddad [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier. Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram. Läs/skriv Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Anger den minsta tidsenheten som representeras på datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Anger binbredden när AggregationType-egenskapens värde är satt till AxisAggregationType.ByBinWidth. Tillämpas på kategori-axlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Anger typen av kategoriaxeln. Läs/skriv [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Representerar punkten på axeln där den ortogonala axeln korsar den. Läs/skriv Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Representerar CrossType på den angivna axeln där den andra axeln korsar. Läs/skriv [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Anger skalningsvärdet för visningsenheterna för värdeaxeln. Läs/skriv [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Representerar formatet för axeln. Skrivskyddad [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Avgör om en axel har en synlig titel. Läs/skriv Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Anger om huvudenheten för axeln tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Anger om maxvärdet tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Anger om subenheten för axeln tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Anger om minvärdet tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Anger automatiskt overflow-binvärde. Om falskt: använd OverflowBin-egenskapen. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Anger automatiskt avstånd för tick-etiketter. Om falskt: använd TickLabelSpacing-egenskapen. Läs/skriv Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Anger automatiskt avstånd för tick-markeringar. Om falskt: använd TickMarksSpacing-egenskapen. Läs/skriv Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Anger automatiskt underflow-binvärde. Om falskt: använd UnderflowBin-egenskapen. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Representerar om värdeaxelns skaltyp är logaritmisk eller inte. Läs/skriv Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Anger om formatet är kopplat till källdata. Läs/skriv Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Anger om overflow-bin tillämpas. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-binvärdet. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs/skriv Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Anger om underflow-bin tillämpas. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-binvärdet. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Representerar om axeln är synlig. Läs/skriv Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Anger avståndet för etiketter från axeln. Tillämpas på kategori- eller datumaxel. Värdet måste vara mellan 0% och 1000%. Läs/skriv UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Representerar den logaritmiska basen. Standardvärdet är 10. Läs/skriv Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Representerar formatet för huvudrutnätslinjer på en diagramaxel. Skrivskyddad [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Representerar typen av huvudtick-markering för den angivna axeln. Läs/skriv [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Representerar huvudenheterna för datum- eller värdeaxeln. Läs/skriv Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Representerar skalan för huvudenheten för datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Representerar det maximala värdet på värdeaxeln. Läs/skriv Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Representerar formatet för sekundära rutnätslinjer på en diagramaxel. Skrivskyddad [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Representerar typen av sekundär tick-markering för den angivna axeln. Läs/skriv [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Representerar de sekundära enheterna för datum- eller värdeaxeln. Läs/skriv Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Representerar skalan för huvudenheten för datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Representerar det minimala värdet på värdeaxeln. Läs/skriv Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Representerar formatsträngen för axeletiketterna. Läs/skriv String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Anger antal bin när AggregationType-egenskapens värde är satt till AxisAggregationType.ByNumberOfBins. Tillämpas på kategori-axlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Anger anpassat overflow-binvärde. Tillämpas när IsAutomaticOverflowBin-egenskapen är falsk och IsOverflowBin-egenskapen är sann. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Representerar axelns position. Läs/skriv [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Representerar om huvudrutnätslinjer visas. Skrivskyddad Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Representerar om sekundära rutnätslinjer visas. Skrivskyddad Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Representerar positionen för tick-etiketterna på den angivna axeln. Läs/skriv [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Representerar rotationsvinkeln för tick-etiketterna. Läs/skriv Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Anger hur många tick-etiketter som ska hoppas över mellan de som ritas. Läs/skriv UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Tillämpas på kategori- eller serieaxel. Läs/skriv UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Hämtar axelns titel. Skrivskyddad [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Anger anpassat underflow-binvärde. Tillämpas när IsAutomaticUnderflowBin-egenskapen är falsk och IsUnderflowBin-egenskapen är sann. |

## Metoder

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Ställer in IAxis.CategoryAxisType-egenskapen med ett värde som bestäms automatiskt baserat på axeldatan. |

### Se även

* gränssnitt [IFormattedTextContainer](../iformattedtextcontainer)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->