---
title: IChartSeries
second_title: Aspose.Sildes dla .NET – odwołanie API
description: Reprezentuje serię wykresu.
type: docs
weight: 1930
url: /pl/aspose.slides.charts/ichartseries/
---
## IChartSeries interfejs

Reprezentuje serię wykresu.

```csharp
public interface IChartSeries : IChartComponent
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Umożliwia pobranie bazowego interfejsu IChartComponent. Tylko do odczytu [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Określa kształt serii wykresu słupkowego 3-D. Zmiana wartości tej właściwości może spowodować automatyczną zmianę typu serii. Odczyt/zapis [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Określa sposób reprezentacji wartości rozmiaru bąbelka na wykresie bąbelkowym. Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.BubbleSizeRepresentation, aby zmienić wartość (odczyt/zapis). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Określa współczynnik skali wykresu bąbelkowego (może wynosić od 0 % do 300 % domyślnego rozmiaru). Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.BubbleSizeScale, aby zmienić wartość (odczyt/zapis). |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Zwraca kolekcję punktów danych tej serii. Tylko do odczytu [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 % do 90 % rozmiaru obszaru wykresu). Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.DoughnutHoleSize, aby zmienić wartość. Tylko do odczytu Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Reprezentuje słupki błędów serii w kierunku X. Słupki błędów w kierunku X są dostępne dla serii typu area, bar, scatter i bubble. Dla innych typów wykresów ta właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z właściwością [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Tylko do odczytu [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Reprezentuje słupki błędów serii w kierunku Y. Słupki błędów w kierunku Y są dostępne dla serii typu area, bar, line, scatter i bubble. Dla innych typów wykresów ta właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z właściwością [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Tylko do odczytu [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Odległość otwartego wycinka tortu od środka wykresu kołowego wyrażona jest jako procent średnicy tortu. Odczyt/zapis Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Określa kąt pierwszego wycinka wykresu kołowego lub pierścieniowego w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 °). Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup.FirstSliceAngle, aby zmienić wartość. Tylko do odczytu UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Zwraca format serii. Tylko do odczytu [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Zwraca lub ustawia odległość, wyrażoną jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup.GapDepth, aby zmienić wartość. Tylko do odczytu Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Określa odstęp między grupami słupków lub kolumn, wyrażony jako procent szerokości słupka lub kolumny. Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup.GapWidth, aby zmienić wartość. Tylko do odczytu Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Określa, czy istnieją linie serii dla tej serii i pokrewnych serii. Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup.HasSeriesLines, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.SeriesLinesFormat, aby sformatować linie serii. Tylko do odczytu Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Określa, czy wykres liniowy lub giełdowy posiada słupki góra/dół. Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup.UpDownBars.HasUpDownBars, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.UpDownBars, aby sformatować słupki góra/dół. Tylko do odczytu Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Określa odwrócony jednolity kolor dla serii. Aby zastosować ustawienie koloru, ustaw format serii FillType na FillType.Solid. Odczyt/zapis [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Określa, czy seria słupków, kolumn lub bąbelków ma odwracać kolory, gdy wartość jest ujemna. Odczyt/zapis Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Określa, że każdy znacznik danych w serii ma inny kolor. Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup.IsColorVaried, aby zmienić wartość. Tylko do odczytu Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Zwraca etykiety serii. Tylko do odczytu [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Zwraca znacznik serii. Tylko do odczytu [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Zwraca nazwę serii. Tylko do odczytu [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Zwraca lub ustawia format liczbowy rozmiarów bąbelków serii. Odczyt/zapis String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Zwraca lub ustawia format liczbowy wartości serii. Odczyt/zapis String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Zwraca lub ustawia format liczbowy wartości X serii. Odczyt/zapis String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Zwraca lub ustawia format liczbowy wartości Y serii. Odczyt/zapis String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Zwraca kolejność serii. Odczyt/zapis Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Określa, jak bardzo słupki i kolumny nachodzą na siebie w wykresach 2-D, wyrażone jako procent (od -100 % do 100 %). Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości w grupie nadrzędnej, dlatego jest tylko do odczytu. Aby zmienić wartość, użyj właściwości ParentSeriesGroup.Overlap. Tylko do odczytu SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Reprezentuje układ etykiet kategorii nadrzędnych. Dotyczy wyłącznie wykresów Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Zwraca grupę serii nadrzędną. Tylko do odczytu [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Określa, w jaki sposób wyznaczyć, które punkty danych znajdują się w drugim wycinku wykresu kołowego lub słupkowego wykresu typu pie-of-pie lub bar-of-pie. Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup.PieSplitBy, aby zmienić wartość. Tylko do odczytu [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Niestandardowe informacje o podziale dla wykresu typu pie-of-pie lub bar-of-pie z podziałem użytkownika. Zawiera punkty danych, które mają być rysowane w drugim wycinku wykresu. Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Tylko do odczytu [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Określa wartość używaną do wyznaczenia, które punkty danych znajdują się w drugim wycinku wykresu pie-of-pie lub bar-of-pie. Stosowana razem z właściwością PieSplitBy. Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup.PieSplitPosition, aby zmienić wartość. Tylko do odczytu Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Wskazuje, czy ta seria jest wykreślana na drugiej osi wartości. Odczyt/zapis Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Reprezentuje metodę kwartylową. Dotyczy wyłącznie wykresów BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Reprezentuje pozycję w legendzie związaną z tą serią. Tylko do odczytu [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Określa rozmiar drugiego wycinka wykresu pie-of-pie lub bar-of-pie jako procent rozmiaru pierwszego wycinka (może wynosić od 5 % do 200 %). Jest to właściwość nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego jest tylko do odczytu. Użyj właściwości ParentSeriesGroup.SecondPieSize, aby zmienić wartość. Tylko do odczytu UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Reprezentuje linie łączące. Dotyczy wyłącznie wykresów Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Reprezentuje wewnętrzne punkty. Prawda, jeśli wewnętrzne punkty są wyświetlane w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Reprezentuje znaczniki średniej. Prawda, jeśli linia średniej jest wyświetlana w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Reprezentuje znaczniki średniej. Prawda, jeśli znaczniki średniej są wyświetlane w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Reprezentuje punkty odstające. Prawda, jeśli punkty odstające są wyświetlane w wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Reprezentuje wygładzanie krzywej. Prawda, jeśli wygładzanie krzywej jest włączone dla wykresu liniowego lub wykresu punktowego połączonego liniami. Dotyczy wyłącznie wykresów liniowych i punktowych połączonych liniami. Odczyt/zapis Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Kolekcja linii trendu serii. Tylko do odczytu [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Zwraca typ tej serii. Odczyt/zapis [`ChartType`](../charttype). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Zwraca automatyczny kolor serii na podstawie indeksu serii i stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType równa się NotDefined. |

### Zobacz także

* interfejs [IChartComponent](../ichartcomponent)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->