---
title: Axis
second_title: Aspose.Sildes dla .NET Referencja API
description: Zawiera obiekt, który reprezentuje oś wykresu.
type: docs
weight: 1160
url: /pl/aspose.slides.charts/axis/
---
## Axis klasa

Zawiera obiekt, który reprezentuje oś wykresu.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Określa rzeczywistą jednostkę główną osi. Wywołaj wcześniej metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Określa rzeczywistą skalę jednostki głównej osi. Wywołaj wcześniej metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Określa rzeczywistą maksymalną wartość na osi. Wywołaj wcześniej metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Określa rzeczywistą jednostkę podrzędną osi. Wywołaj wcześniej metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Określa rzeczywistą skalę jednostki podrzędnej osi. Wywołaj wcześniej metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Określa rzeczywistą minimalną wartość na osi. Wywołaj wcześniej metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Reprezentuje typ agregacji osi kategorii (grupowanie). Stosowany do kategorii. Używany wyłącznie z seriami Histogram lub HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Informuje, czy oś wartości przecina oś kategorii pomiędzy kategoriami. Ta właściwość ma zastosowanie tylko do osi kategorii i nie obowiązuje w wykresach 3-D. Do odczytu i zapisu Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. Do odczytu i zapisu [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Określa szerokość przedziału, gdy właściwość AggregationType ma wartość AxisAggregationType.ByBinWidth. Stosowany do osi kategorii. Używany wyłącznie z seriami Histogram lub HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Określa typ osi kategorii. Do odczytu i zapisu [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Zwraca wykres nadrzędny. Tylko do odczytu [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Reprezentuje punkt na osi, w którym prostopadła oś ją przecina. Do odczytu i zapisu Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Reprezentuje typ przecięcia (CrossType) na określonej osi, w którym przecina ją inna oś. Do odczytu i zapisu [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Określa wartość skalowania jednostek wyświetlania dla osi wartości. Do odczytu i zapisu [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Reprezentuje format osi. Tylko do odczytu [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Określa, czy oś ma widoczny tytuł. Do odczytu i zapisu Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Wskazuje, czy jednostka główna osi jest przypisywana automatycznie. Do odczytu i zapisu Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. Do odczytu i zapisu Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Wskazuje, czy jednostka podrzędna osi jest przypisywana automatycznie. Do odczytu i zapisu Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Wskazuje, czy minimalna wartość jest przypisywana automatycznie. Do odczytu i zapisu Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Określa automatyczną wartość przedziału przepełnienia. Jeśli false: użyj właściwości OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Określa automatyczną wartość odstępu etykiet znacznika. Jeśli false: użyj właściwości TickLabelSpacing. Do odczytu i zapisu Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Określa automatyczną wartość odstępu znaczników. Jeśli false: użyj właściwości TickMarksSpacing. Do odczytu i zapisu Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Określa automatyczną wartość przedziału podprzepływu. Jeśli false: użyj właściwości UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Informuje, czy typ skali osi wartości jest logarytmiczny. Do odczytu i zapisu Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Wskazuje, czy format jest powiązany z danymi źródłowymi. Do odczytu i zapisu Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Określa, czy zastosowano przedział przepełnienia. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość przedziału przepełnienia. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Informuje, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. Do odczytu i zapisu Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Określa, czy zastosowano przedział podprzepływu. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość przedziału podprzepływu. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Informuje, czy oś jest widoczna. Do odczytu i zapisu Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Określa odległość etykiet od osi. Stosowane do osi kategorii lub daty. Wartość musi mieścić się w przedziale od 0% do 1000%. Do odczytu i zapisu UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Reprezentuje podstawę logarytmu. Domyślna wartość to 10. Do odczytu i zapisu Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Reprezentuje format głównych linii siatki na osi wykresu. Tylko do odczytu [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Reprezentuje typ głównego znacznika na określonej osi. Do odczytu i zapisu [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Reprezentuje jednostki główne dla osi daty lub wartości. Do odczytu i zapisu Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Reprezentuje skalę jednostki głównej dla osi daty. Do odczytu i zapisu [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Reprezentuje maksymalną wartość na osi wartości. Do odczytu i zapisu Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Reprezentuje format podrzędnych linii siatki na osi wykresu. Tylko do odczytu [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Reprezentuje typ podrzędnego znacznika na określonej osi. Do odczytu i zapisu [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Reprezentuje jednostki podrzędne dla osi daty lub wartości. Do odczytu i zapisu Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Reprezentuje skalę jednostki głównej dla osi daty. Do odczytu i zapisu [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Reprezentuje minimalną wartość na osi wartości. Do odczytu i zapisu Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Reprezentuje ciąg formatowania etykiet osi. Do odczytu i zapisu String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Określa liczbę przedziałów, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByNumberOfBins. Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Określa niestandardową wartość przedziału przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i właściwość IsOverflowBin ma wartość true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Reprezentuje pozycję osi. Do odczytu i zapisu [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Aby ukryć główną linię siatki, ustaw MajorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Tylko do odczytu Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Aby ukryć podrzędną linię siatki, ustaw MinorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Tylko do odczytu Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Reprezentuje format tekstu. Tylko do odczytu [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Reprezentuje pozycję etykiet znaczników na określonej osi. Do odczytu i zapisu [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Reprezentuje kąt obrotu etykiet znaczników. Do odczytu i zapisu Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Określa, ile etykiet znaczników pomijać między rysowanymi etykietami. Stosowane do osi kategorii lub serii. Do odczytu i zapisu UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Określa, ile znaczników pomijać przed narysowaniem kolejnego. Stosowane do osi kategorii lub serii. Do odczytu i zapisu UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Zwraca tytuł osi. Tylko do odczytu [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Określa niestandardową wartość przedziału podprzepływu. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i właściwość IsUnderflowBin ma wartość true. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Ustawia właściwość IAxis.CategoryAxisType na wartość określaną automatycznie na podstawie danych osi. |

### Zobacz także

* klasa [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* klasa [AxesManager](../axesmanager)
* interfejs [IAxis](../iaxis)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->