---
title: IAxis
second_title: Aspose.Sildes dla .NET – referencja API
description: Enkapsuluje obiekt, który reprezentuje oś wykresu.
type: docs
weight: 1690
url: /pl/aspose.slides.charts/iaxis/
---
## IAxis interfejs

Enkapsuluje obiekt, który reprezentuje oś wykresu.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Określa rzeczywistą jednostkę główną osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Określa rzeczywistą skalę jednostki głównej osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Określa rzeczywistą maksymalną wartość na osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Określa rzeczywistą jednostkę poboczną osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Określa rzeczywistą skalę jednostki pobocznej osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Określa rzeczywistą minimalną wartość na osi. Najpierw wywołaj metodę IChart.ValidateChartLayout(), aby uzyskać rzeczywistą wartość. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Reprezentuje typ agregacji osi kategorii (binnowanie). Stosowane do kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Umożliwia pobranie bazowego interfejsu IFormattedTextContainer. Tylko do odczytu [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Reprezentuje, czy oś wartości przecina oś kategorii pomiędzy kategoriami. Właściwość dotyczy tylko osi kategorii i nie ma zastosowania w wykresach 3D. Odczyt/zapis Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Określa najmniejszą jednostkę czasu reprezentowaną na osi daty. Odczyt/zapis [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Określa szerokość kosza, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByBinWidth. Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Określa typ osi kategorii. Odczyt/zapis [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Reprezentuje punkt na osi, w którym okrężna oś przecina ją. Odczyt/zapis Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Reprezentuje CrossType na określonej osi, w którym inna oś ją przecina. Odczyt/zapis [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Określa wartość skalowania jednostek wyświetlania dla osi wartości. Odczyt/zapis [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Reprezentuje format osi. Tylko do odczytu [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Określa, czy oś posiada widoczny tytuł. Odczyt/zapis Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Wskazuje, czy jednostka główna osi jest przypisywana automatycznie. Odczyt/zapis Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Wskazuje, czy maksymalna wartość jest przypisywana automatycznie. Odczyt/zapis Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Wskazuje, czy jednostka poboczna osi jest przypisywana automatycznie. Odczyt/zapis Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Wskazuje, czy minimalna wartość jest przypisywana automatycznie. Odczyt/zapis Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Określa automatyczną wartość kosza przepełnienia. Jeśli false: użyj właściwości OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Określa automatyczną wartość odstępu etykiet znaczników. Jeśli false: użyj właściwości TickLabelSpacing. Odczyt/zapis Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Określa automatyczną wartość odstępu znaczników. Jeśli false: użyj właściwości TickMarksSpacing. Odczyt/zapis Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Określa automatyczną wartość kosza podprzepływu. Jeśli false: użyj właściwości UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Reprezentuje, czy typ skali osi wartości jest logarytmiczny. Odczyt/zapis Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Wskazuje, czy format jest powiązany z danymi źródłowymi. Odczyt/zapis Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Określa, czy kosz przepełnienia jest stosowany. Użyj IsAutomaticOverflowBin i OverflowBin, aby dostosować wartość kosza przepełnienia. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Reprezentuje, czy MS PowerPoint rysuje punkty danych od ostatniego do pierwszego. Odczyt/zapis Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Określa, czy kosz podprzepływu jest stosowany. Użyj IsAutomaticUnderflowBin i UnderflowBin, aby dostosować wartość kosza podprzepływu. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Reprezentuje, czy oś jest widoczna. Odczyt/zapis Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Określa odległość etykiet od osi. Stosowane do osi kategorii lub daty. Wartość musi mieścić się w przedziale od 0% do 1000%. Odczyt/zapis UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Reprezentuje podstawę logarytmu. Domyślna wartość to 10. Odczyt/zapis Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Reprezentuje format głównych linii siatki na osi wykresu. Tylko do odczytu [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Reprezentuje typ głównego znacznika na określonej osi. Odczyt/zapis [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Reprezentuje jednostki główne dla osi daty lub wartości. Odczyt/zapis Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Reprezentuje skalę jednostki głównej dla osi daty. Odczyt/zapis [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Reprezentuje maksymalną wartość na osi wartości. Odczyt/zapis Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Reprezentuje format mniejszych linii siatki na osi wykresu. Tylko do odczytu [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Reprezentuje typ mniejszego znacznika na określonej osi. Odczyt/zapis [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Reprezentuje jednostki poboczne dla osi daty lub wartości. Odczyt/zapis Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Reprezentuje skalę jednostki głównej dla osi daty. Odczyt/zapis [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Reprezentuje minimalną wartość na osi wartości. Odczyt/zapis Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Reprezentuje ciąg formatu dla etykiet osi. Odczyt/zapis String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Określa liczbę koszy, gdy wartość właściwości AggregationType jest ustawiona na AxisAggregationType.ByNumberOfBins. Stosowane do osi kategorii. Używane wyłącznie z seriami Histogram lub HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Określa niestandardową wartość kosza przepełnienia. Stosowane, gdy właściwość IsAutomaticOverflowBin jest ustawiona na false i właściwość IsOverflowBin ma wartość true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Reprezentuje pozycję osi. Odczyt/zapis [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Reprezentuje, czy główne linie siatki są wyświetlane. Tylko do odczytu Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Reprezentuje, czy poboczne linie siatki są wyświetlane. Tylko do odczytu Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Reprezentuje pozycję etykiet znaczników na określonej osi. Odczyt/zapis [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Reprezentuje kąt obrotu etykiet znaczników. Odczyt/zapis Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Określa, ile etykiet znaczników pominąć pomiędzy wyświetlanymi etykietami. Odczyt/zapis UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Określa, ile znaczników pominąć przed narysowaniem kolejnego. Stosowane do osi kategorii lub serii. Odczyt/zapis UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Pobiera tytuł osi. Tylko do odczytu [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Określa niestandardową wartość kosza podprzepływu. Stosowane, gdy właściwość IsAutomaticUnderflowBin jest ustawiona na false i właściwość IsUnderflowBin ma wartość true. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Ustawia właściwość IAxis.CategoryAxisType na wartość automatycznie określaną na podstawie danych osi. |

### Zobacz także

* interfejs [IFormattedTextContainer](../iformattedtextcontainer)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->