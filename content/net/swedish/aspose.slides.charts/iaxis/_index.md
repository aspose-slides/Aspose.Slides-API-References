---
title: IAxis
second_title: Aspose.Sildes för .NET API-referens
description: Inkapslar objektet som representerar ett diagramaxel.
type: docs
weight: 1690
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
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Anger den faktiska skalan för huvudenheten på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Anger det faktiska maximivärdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Anger den faktiska underenheten för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Anger den faktiska skalan för underenheten på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Anger det faktiska minimivärdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Representerar aggregeringstyp för kategoriaxel (gruppering). Tillämpars på kategori. Används endast med Histogram- eller HistogramPareto-serier. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Tillåter att hämta bas-IFormattedTextContainer-gränssnittet. Skrivskyddad [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier. Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram. Läs/skriv Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Anger den minsta tidsenheten som representeras på datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Anger binbredden när egenskapen AggregationType har värdet AxisAggregationType.ByBinWidth. Tillämpars på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Anger typen av kategoriaxel. Läs/skriv [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Representerar punkten på axeln där den vinkelräta axeln korsar den. Läs/skriv Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Representerar CrossType på den angivna axeln där den andra axeln korsar. Läs/skriv [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Anger skalningsvärdet för visningsenheterna på värdeaxeln. Läs/skriv [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Representerar formatet för axeln. Skrivskyddad [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Avgör om en axel har en synlig titel. Läs/skriv Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Anger om huvudenheten för axeln tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Anger om maximivärdet tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Anger om underenheten för axeln tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Anger om minimivärdet tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Anger automatiskt översvämningsbinvärde. Om falskt: använd egenskapen OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Anger automatiskt avstånd för tick-etiketter. Om falskt: använd egenskapen TickLabelSpacing. Läs/skriv Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Anger automatiskt avstånd för tick-markeringar. Om falskt: använd egenskapen TickMarksSpacing. Läs/skriv Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Anger automatiskt underflödesbinvärde. Om falskt: använd egenskapen UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Representerar om skaltypen för värdeaxeln är logaritmisk eller inte. Läs/skriv Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Anger om formatet är länkat till källdata. Läs/skriv Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Anger om översvämningsbin tillämpas. Använd IsAutomaticOverflowBin och OverflowBin för att justera översvämningsbinvärdet. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs/skriv Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Anger om underflödesbin tillämpas. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflödesbinvärdet. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Representerar om axeln är synlig. Läs/skriv Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Anger avståndet för etiketter från axeln. Tillämpas på kategori- eller datumaxel. Värdet måste vara mellan 0 % och 1000 %. Läs/skriv UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Representerar den logaritmiska basen. Standardvärdet är 10. Läs/skriv Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Representerar formatet för huvudnätlinjer på en diagramaxel. Skrivskyddad [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Representerar typen av huvud-tick-märke för den angivna axeln. Läs/skriv [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Representerar huvud-enheterna för datum- eller värdeaxeln. Läs/skriv Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Representerar skalan för huvud-enheten på datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Representerar maximivärdet på värdeaxeln. Läs/skriv Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Representerar formatet för undernätlinjer på en diagramaxel. Skrivskyddad [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Representerar typen av under-tick-märke för den angivna axeln. Läs/skriv [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Representerar under-enheterna för datum- eller värdeaxeln. Läs/skriv Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Representerar skalan för huvud-enheten på datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Representerar minimivärdet på värdeaxeln. Läs/skriv Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Representerar formatsträngen för axel-etiketterna. Läs/skriv String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Anger antalet bin när egenskapen AggregationType har värdet AxisAggregationType.ByNumberOfBins. Tillämpars på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Anger anpassat värde för översvämningsbin. Tillämpars när egenskapen IsAutomaticOverflowBin är falsk och egenskapen IsOverflowBin är sann. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Representerar axelns position. Läs/skriv [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Representerar om huvudnätlinjerna visas. Skrivskyddad Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Representerar om undernätlinjerna visas. Skrivskyddad Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Representerar positionen för tick-märkeetiketterna på den angivna axeln. Läs/skriv [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Representerar rotationsvinkeln för tick-etiketterna. Läs/skriv Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Anger hur många tick-etiketter som ska hoppas över mellan ritade etiketter. Läs/skriv UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Tillämpars på kategori- eller serieaxel. Läs/skriv UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Hämtar axelns titel. Skrivskyddad [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Anger anpassat värde för underflödesbin. Tillämpars när egenskapen IsAutomaticUnderflowBin är falsk och egenskapen IsUnderflowBin är sann. |

## Metoder

| Name | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Anger IAxis.CategoryAxisType-egenskapen med ett värde som bestäms automatiskt baserat på axeldata. |

### Se även

* gränssnitt [IFormattedTextContainer](../iformattedtextcontainer)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->