---
title: Axis
second_title: Aspose.Sildes dla .NET - dokumentacja API
description: Enkapsuluje obiekt, który reprezentuje oś wykresu.
type: docs
weight: 1180
url: /pl/aspose.slides.charts/axis/
---
## Axis klasa

Enkapsuluje obiekt, który reprezentuje oś wykresu.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Określa rzeczywistą jednostkę główną osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Określa rzeczywistą skalę jednostki głównej osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Określa rzeczywistą maksymalną wartość na osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Określa rzeczywistą jednostkę podrzędną osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Określa rzeczywistą skalę jednostki podrzędnej osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Określa rzeczywistą minimalną wartość na osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Reprezentuje typ agregacji osi kategorii (grupowanie). Stosowane do kategorii. Używane wyłącznie w seriach Histogram lub HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Określa, czy oś wartości przecina oś kategorii pomiędzy kategoriami. Właściwość ma zastosowanie tylko do osi kategorii i nie obowiązuje w wykresach 3D. Odczyt/zapis Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. Odczyt/zapis [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Określa szerokość kosza, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByBinWidth. Stosowane do osi kategorii. Używane wyłącznie w seriach Histogram lub HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Określa typ osi kategorii. Odczyt/zapis [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Zwraca nadrzędny wykres. Tylko do odczytu [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Reprezentuje punkt na osi, w którym przecina ją oś prostopadła. Odczyt/zapis Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Reprezentuje CrossType na określonej osi, w którym druga oś ją przecina. Odczyt/zapis [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Określa wartość skalowania jednostek wyświetlania dla osi wartości. Odczyt/zapis [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Reprezentuje format osi. Tylko do odczytu [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Określa, czy oś ma widoczny tytuł. Odczyt/zapis Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Wskazuje, czy jednostka główna osi jest przydzielana automatycznie. Odczyt/zapis Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Wskazuje, czy maksymalna wartość jest przydzielana automatycznie. Odczyt/zapis Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Wskazuje, czy jednostka podrzędna osi jest przydzielana automatycznie. Odczyt/zapis Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Wskazuje, czy minimalna wartość jest przydzielana automatycznie. Odczyt/zapis Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Określa automatyczną wartość kosza przepełnienia. Jeśli false: użyj właściwości OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Określa automatyczną wartość odstępu etykiet znaczników. Jeśli false: użyj właściwości TickLabelSpacing. Odczyt/zapis Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Określa automatyczną wartość odstępu znaczników. Jeśli false: użyj właściwości TickMarksSpacing. Odczyt/zapis Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Określa automatyczną wartość kosza podprzepływu. Jeśli false: użyj właściwości UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Określa, czy typ skali osi wartości jest logarytmiczny. Odczyt/zapis Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Wskazuje, czy format jest powiązany z danymi źródłowymi. Odczyt/zapis Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Określa, czy kosz przepełnienia jest stosowany. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość kosza przepełnienia. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Określa, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. Odczyt/zapis Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Określa, czy kosz podprzepływu jest stosowany. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość kosza podprzepływu. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Określa, czy oś jest widoczna. Odczyt/zapis Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Określa odległość etykiet od osi. Stosowane do osi kategorii lub daty. Wartość musi wynosić od 0% do 1000%. Odczyt/zapis UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Reprezentuje podstawę logarytmu. Domyślna wartość to 10. Odczyt/zapis Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Reprezentuje format głównych linii siatki na osi wykresu. Tylko do odczytu [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Reprezentuje typ głównego znacznika na określonej osi. Odczyt/zapis [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Reprezentuje jednostki główne dla osi daty lub wartości. Odczyt/zapis Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Reprezentuje skalę jednostki głównej dla osi daty. Odczyt/zapis [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Reprezentuje maksymalną wartość na osi wartości. Odczyt/zapis Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Reprezentuje format mniejszych linii siatki na osi wykresu. Tylko do odczytu [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Reprezentuje typ mniejszego znacznika na określonej osi. Odczyt/zapis [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Reprezentuje jednostki mniejsze dla osi daty lub wartości. Odczyt/zapis Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Reprezentuje skalę jednostki głównej dla osi daty. Odczyt/zapis [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Reprezentuje minimalną wartość na osi wartości. Odczyt/zapis Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Reprezentuje ciąg formatu dla Axis Labels. Odczyt/zapis String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Określa liczbę koszy, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByNumberOfBins. Stosowane do osi kategorii. Używane wyłącznie w seriach Histogram lub HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Określa niestandardową wartość kosza przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i właściwość IsOverflowBin ma wartość true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Reprezentuje pozycję osi. Odczyt/zapis [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Aby ukryć główną linię siatki, ustaw MajorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Tylko do odczytu Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Aby ukryć mniejszą linię siatki, ustaw MinorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Tylko do odczytu Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Reprezentuje format tekstu. Tylko do odczytu [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Reprezentuje pozycję etykiet znaczników na określonej osi. Odczyt/zapis [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Reprezentuje kąt obrotu etykiet znaczników. Odczyt/zapis Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Określa, ile etykiet znaczników pomijać pomiędzy rysowanymi etykietami. Stosowane do osi kategorii lub serii. Odczyt/zapis UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Określa, ile znaczników pomijać przed narysowaniem kolejnego. Stosowane do osi kategorii lub serii. Odczyt/zapis UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Pobiera tytuł osi. Tylko do odczytu [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Określa niestandardową wartość kosza podprzepływu. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i właściwość IsUnderflowBin ma wartość true. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Ustawia właściwość IAxis.CategoryAxisType na wartość automatycznie określoną na podstawie danych osi. |

### Patrz także

* klasa [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* klasa [AxesManager](../axesmanager)
* interfejs [IAxis](../iaxis)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->