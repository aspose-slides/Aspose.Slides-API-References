---
title: Axis
second_title: Aspose.Sildes för .NET API-referens
description: Inkapslar objektet som representerar en diagramaxel.
type: docs
weight: 1180
url: /sv/aspose.slides.charts/axis/
---
## Axis klass

Inkapslar objektet som representerar diagrammets axel.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Anger det faktiska huvudvärdet för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Anger den faktiska huvudvärdeskalan för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Anger det faktiska maximala värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Anger det faktiska mindre enhetsvärdet för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Anger den faktiska mindre enhetsskalan för axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Anger det faktiska minimala värdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Representerar aggregeringstyp för kategoriaxeln (binning). Tillämpars på kategori. Används endast med Histogram- eller HistogramPareto-serier. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Anger om värdeaxeln korsar kategoriaxeln mellan kategorier. Denna egenskap gäller endast kategoriaxlar och gäller inte för 3-D-diagram. Läs/skriv Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Anger den minsta tidsenheten som representeras på datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Anger binbredd när AggregationType-egenskapens värde är satt till AxisAggregationType.ByBinWidth. Tillämpars på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Anger typen av kategoriaxel. Läs/skriv [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Returnerar det överordnade diagrammet. Endast läsning [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Representerar den punkt på axeln där den vinkelräta axeln korsar den. Läs/skriv Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Representerar CrossType på den angivna axeln där den andra axeln korsar. Läs/skriv [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Anger skaleringsvärdet för visningsenheter för värdeaxeln. Läs/skriv [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Representerar formatet för axeln. Endast läsning [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Anger om en axel har en synlig titel. Läs/skriv Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indikerar om huvudvärdet för axeln tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indikerar om maxvärdet tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indikerar om det mindre enhetsvärdet för axeln tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indikerar om minvärdet tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Anger automatiskt overflow-bin-värde. Om falskt: använd OverflowBin-egenskapen. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Anger automatiskt avstånd för tick-etiketter. Om falskt: använd TickLabelSpacing-egenskapen. Läs/skriv Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Anger automatiskt avstånd för tick-markeringar. Om falskt: använd TickMarksSpacing-egenskapen. Läs/skriv Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Anger automatiskt underflow-bin-värde. Om falskt: använd UnderflowBin-egenskapen. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Representerar om skalentypen för värdeaxeln är logaritmisk eller ej. Läs/skriv Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indikerar om formatet är länkat till källdata. Läs/skriv Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Anger om overflow-bin tillämpas. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Representerar om MS PowerPoint plotter data från sista till första. Läs/skriv Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Anger om underflow-bin tillämpas. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Representerar om axeln är synlig. Läs/skriv Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Anger avståndet för etiketter från axeln. Tillämpars på kategori- eller datumaxel. Värdet måste ligga mellan 0 % och 1000 %. Läs/skriv UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Representerar den logaritmiska basen. Standardvärdet är 10. Läs/skriv Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Representerar huvudrutnätslinjernas format på en diagramaxel. Endast läsning [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Representerar typen av huvud-tick-markering för den angivna axeln. Läs/skriv [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Representerar huvud-enheterna för datum- eller värdeaxel. Läs/skriv Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Representerar huvud-enhetsskalan för datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Representerar det maximala värdet på värdeaxeln. Läs/skriv Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Representerar mindre rutnätslinjernas format på en diagramaxel. Endast läsning [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Representerar typen av mindre tick-markering för den angivna axeln. Läs/skriv [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Representerar de mindre enheterna för datum- eller värdeaxel. Läs/skriv Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Representerar huvud-enhetsskalan för datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Representerar minvärdet på värdeaxeln. Läs/skriv Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Representerar formatsträngen för axel-etiketterna. Läs/skriv String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Anger antal bin när AggregationType-egenskapens värde är satt till AxisAggregationType.ByNumberOfBins. Tillämpars på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Anger anpassat overflow-bin-värde. Tillämpars när IsAutomaticOverflowBin är falskt och IsOverflowBin är true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Representerar axelns position. Läs/skriv [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | För att dölja huvudrutnätslinjen, sätt MajorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. Endast läsning Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | För att dölja mindre rutnätslinjen, sätt MinorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. Endast läsning Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Representerar textformatet. Endast läsning [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Representerar positionen för tick-etiketter på den angivna axeln. Läs/skriv [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Representerar rotationsvinkeln för tick-etiketter. Läs/skriv Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Anger hur många tick-etiketter som ska hoppas över mellan två ritade etiketter. Tillämpars på kategori- eller serieaxel. Läs/skriv UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Anger hur många tick-markeringar som ska hoppas över före nästa ritas. Tillämpars på kategori- eller serieaxel. Läs/skriv UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Hämtar axelns titel. Endast läsning [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Anger anpassat underflow-bin-värde. Tillämpars när IsAutomaticUnderflowBin är falskt och IsUnderflowBin är true. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Sätter IAxis.CategoryAxisType-egenskapen med ett värde som automatiskt bestäms baserat på axeldata. |

### Se även

* klass [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* klass [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->