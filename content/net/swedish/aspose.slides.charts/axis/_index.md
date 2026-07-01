---
title: Axis
second_title: Aspose.Sildes för .NET API-referens
description: Inkapslar objektet som representerar ett diagramaxel.
type: docs
weight: 1160
url: /sv/aspose.slides.charts/axis/
---
## Axis klass

Inkapslar objektet som representerar ett diagramaxel.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Anger det faktiska huvudvärdet för enheten på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Anger den faktiska skalan för huvudvärdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Anger det faktiska maximivärdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Anger den faktiska mindre enheten på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Anger den faktiska skalan för den mindre enheten på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Anger det faktiska minimivärdet på axeln. Anropa metoden IChart.ValidateChartLayout() tidigare för att få det faktiska värdet. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Representerar aggregeringstyp för kategoriaxel (binnning). Appliceras på kategori. Används endast med Histogram- eller HistogramPareto-serier. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Representerar om värdeaxeln korsar kategoriaxeln mellan kategorier. Denna egenskap gäller endast för kategoriaxlar och gäller inte för 3-D-diagram. Läs/skriv Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Anger den minsta tidsenheten som representeras på datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Anger binbredden när egenskapen AggregationType har värdet AxisAggregationType.ByBinWidth. Appliceras på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Anger typen av kategoriaxeln. Läs/skriv [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Returnerar det överordnade diagrammet. Skrivskyddad [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Representerar punkten på axeln där den vinkelräta axeln korsar den. Läs/skriv Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Representerar CrossType på den angivna axeln där den andra axeln korsar. Läs/skriv [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Anger skalningsvärdet för visningsenheterna för värdeaxeln. Läs/skriv [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Representerar formatet för axeln. Skrivskyddad [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Bestämmer om en axel har en synlig titel. Läs/skriv Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indikerar om huvudvärdet för axeln tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indikerar om det maximala värdet tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indikerar om den mindre enheten för axeln tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indikerar om det minsta värdet tilldelas automatiskt. Läs/skriv Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Anger automatiskt overflow-bin-värde. Om false: använd egenskapen OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Anger automatiskt värde för avstånd mellan tick-etiketter. Om false: använd egenskapen TickLabelSpacing. Läs/skriv Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Anger automatiskt värde för avstånd mellan tick-markeringar. Om false: använd egenskapen TickMarksSpacing. Läs/skriv Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Anger automatiskt underflow-bin-värde. Om false: använd egenskapen UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Representerar om skala-typen för värdeaxeln är logaritmisk eller inte. Läs/skriv Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indikerar om formatet länkas till källdata. Läs/skriv Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Anger om overflow-bin tillämpas. Använd IsAutomaticOverflowBin och OverflowBin för att justera overflow-bin-värdet. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Representerar om MS PowerPoint ritar datapunkter från sista till första. Läs/skriv Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Anger om underflow-bin tillämpas. Använd IsAutomaticUnderflowBin och UnderflowBin för att justera underflow-bin-värdet. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Representerar om axeln är synlig. Läs/skriv Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Anger avståndet för etiketter från axeln. Appliceras på kategori- eller datumaxel. Värdet måste vara mellan 0% och 1000%. Läs/skriv UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Representerar den logaritmiska basen. Standardvärdet är 10. Läs/skriv Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Representerar formatet för huvudrutnät på en diagramaxel. Skrivskyddad [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Representerar typen av huvud-tick-markering för den angivna axeln. Läs/skriv [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Representerar huvud-enheterna för datum- eller värdeaxeln. Läs/skriv Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Representerar huvud-enhetsskalan för datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Representerar det maximala värdet på värdeaxeln. Läs/skriv Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Representerar formatet för mindre rutnät på en diagramaxel. Skrivskyddad [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Representerar typen av mindre tick-markering för den angivna axeln. Läs/skriv [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Representerar de mindre enheterna för datum- eller värdeaxeln. Läs/skriv Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Representerar huvud-enhetsskalan för datumaxeln. Läs/skriv [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Representerar det minsta värdet på värdeaxeln. Läs/skriv Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Representerar formatsträngen för Axis Labels. Läs/skriv String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Anger antalet bin när egenskapen AggregationType har värdet AxisAggregationType.ByNumberOfBins. Appliceras på kategoriaxlar. Används endast med Histogram- eller HistogramPareto-serier. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Anger anpassat värde för overflow-bin. Appliceras när egenskapen IsAutomaticOverflowBin har värdet false och egenskapen IsOverflowBin är true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Representerar positionen för axeln. Läs/skriv [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | För att dölja huvudrutnät, sätt MajorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. Skrivskyddad Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | För att dölja mindre rutnät, sätt MinorGridLinesFormat.Line.FillFormat.FillType till FillType.NoFill. Skrivskyddad Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Representerar formatet för text. Skrivskyddad [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Representerar positionen för tick-etikettmarkeringar på den angivna axeln. Läs/skriv [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Representerar rotationsvinkeln för tick-etiketter. Läs/skriv Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Anger hur många tick-etiketter som ska hoppas över mellan de som ritas. Appliceras på kategori- eller serieaxel. Läs/skriv UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Anger hur många tick-markeringar som ska hoppas över innan nästa ritas. Appliceras på kategori- eller serieaxel. Läs/skriv UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Hämtar axelns titel. Skrivskyddad [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Anger anpassat värde för underflow-bin. Appliceras när egenskapen IsAutomaticUnderflowBin har värdet false och egenskapen IsUnderflowBin är true. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Ställer in egenskapen IAxis.CategoryAxisType med ett värde som bestäms automatiskt baserat på axeldata. |

### Se även

* klass [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* klass [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->