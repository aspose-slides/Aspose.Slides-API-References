---
title: ChartSeries
second_title: Aspose.Sildes dla .NET – referencja API
description: Reprezentuje serię wykresu.
type: docs
weight: 1440
url: /pl/aspose.slides.charts/chartseries/
---
## ChartSeries klasa

Reprezentuje serię wykresu.

```csharp
public class ChartSeries : IChartSeries
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Określa kształt serii wykresu słupkowego 3-D. Zmiana wartości tej właściwości może spowodować automatyczną zmianę typu serii. Odczyt/zapis [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Określa, jak wartości rozmiaru bąbelka są reprezentowane na wykresie bąbelkowym. Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.BubbleSizeRepresentation odczyt/zapis, aby zmienić wartość. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Określa współczynnik skali dla wykresu bąbelkowego (może wynosić od 0 do 300 % domyślnego rozmiaru). Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.BubbleSizeScale odczyt/zapis, aby zmienić wartość. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Zwraca nadrzędny wykres. Tylko do odczytu [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Zwraca kolekcję punktów danych tej serii. Tylko do odczytu [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 % rozmiaru obszaru wykresu). Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.DoughnutHoleSize odczyt/zapis, aby zmienić wartość. Tylko do odczytu Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Reprezentuje paski błędów serii z kierunkiem X. Paski błędów w kierunku X są dostępne dla serii typu area, bar, scatter i bubble. Dla innych typów wykresów ta właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z właściwością [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Tylko do odczytu [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Reprezentuje paski błędów serii z kierunkiem Y. Paski błędów w kierunku Y są dostępne dla serii typu area, bar, line, scatter i bubble. Dla innych typów wykresów ta właściwość zwraca null (w tym wykresy 3D). W przypadku wartości niestandardowych użyj kolekcji DataPoints, aby określić wartość (z właściwością [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Tylko do odczytu [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Odległość otwartego kawałka koła od środka wykresu kołowego wyrażona jest jako procent średnicy koła. Odczyt/zapis Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Określa kąt pierwszego kawałka wykresu kołowego lub pierścieniowego w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.FirstSliceAngle odczyt/zapis, aby zmienić wartość. Tylko do odczytu UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Zwraca format serii. Tylko do odczytu [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Zwraca lub ustawia odległość, wyrażoną jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.GapDepth odczyt/zapis, aby zmienić wartość. Tylko do odczytu Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Określa odległość pomiędzy grupami słupków lub kolumn, wyrażoną jako procent szerokości słupka lub kolumny. Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.GapWidth odczyt/zapis, aby zmienić wartość. Tylko do odczytu Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Określa, czy dla tej serii i pokrewnych serii istnieją linie serii. Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.HasSeriesLines odczyt/zapis, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.SeriesLinesFormat, aby sformatować linie serii. Tylko do odczytu Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Określa, czy wykres liniowy lub giełdowy posiada słupki w górę/dół. Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.UpDownBars.HasUpDownBars odczyt/zapis, aby zmienić wartość. Użyj właściwości ParentSeriesGroup.UpDownBars, aby sformatować słupki w górę/dół. Tylko do odczytu Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Określa odwrócony jednolity kolor dla serii. Aby zastosować ustawienie koloru, ustaw format serii FillType na FillType.Solid. Odczyt/zapis [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Określa, że seria słupków, kolumn lub bąbelków powinna odwrócić kolory, jeśli wartość jest ujemna. Odczyt/zapis Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Określa, że każdy znacznik danych w serii ma inny kolor. Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.IsColorVaried odczyt/zapis, aby zmienić wartość. Tylko do odczytu Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Zwraca etykiety serii. Tylko do odczytu [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Znacznik. Tylko do odczytu [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Zwraca nazwę serii. Tylko do odczytu [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Odczyt/zapis String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Odczyt/zapis String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Odczyt/zapis String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Odczyt/zapis String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Zwraca kolejność serii. Odczyt/zapis Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Określa, o ile słupki i kolumny zachodzą na siebie na wykresach 2-D, wyrażone jako procent (od -100 % do 100 %). Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej. Jest to projekcja odpowiedniej właściwości w grupie serii nadrzędnej, dlatego ta właściwość jest tylko do odczytu. Aby zmienić wartość, użyj właściwości !:ParentSeriesGroup.Overlap odczyt/zapis. Tylko do odczytu SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Reprezentuje układ etykiet kategorii nadrzędnej. Dotyczy wyłącznie wykresów Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Tylko do odczytu [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Określa, jak ustalić, które punkty danych znajdują się w drugim kole lub słupku na wykresie pie-of-pie lub bar-of-pie. Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.PieSplitBy odczyt/zapis, aby zmienić wartość. Tylko do odczytu [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Informacje o niestandardowym podziale dla wykresu pie-of-pie lub bar-of-pie z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim kole lub słupku w wykresie pie-of-pie lub bar-of-pie. Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Tylko do odczytu [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim kole lub słupku na wykresie pie-of-pie lub bar-of-pie. Używana jest razem z właściwością PieSplitBy. Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.PieSplitPosition odczyt/zapis, aby zmienić wartość. Tylko do odczytu Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Wskazuje, czy ta seria jest rysowana na drugiej osi. Odczyt/zapis Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Reprezentuje metodę kwartyli. Dotyczy wyłącznie wykresów BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Reprezentuje wpis legendy związany z tą serią. Tylko do odczytu [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Określa rozmiar drugiego koła lub słupka wykresu pie-of-pie lub bar-of-pie, wyrażony jako procent rozmiaru pierwszego koła (może wynosić od 5 do 200 %). Ta właściwość dotyczy nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj właściwości ParentSeriesGroup.SecondPieSize odczyt/zapis, aby zmienić wartość. Tylko do odczytu UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Reprezentuje linie łączące. Dotyczy wyłącznie wykresów Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Reprezentuje wewnętrzne punkty. Prawda, jeśli wewnętrzne punkty są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Reprezentuje linię średniej. Prawda, jeśli linia średniej jest wyświetlana na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Reprezentuje znaczniki średniej. Prawda, jeśli znaczniki średniej są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Reprezentuje punkty odstające. Prawda, jeśli punkty odstające są wyświetlane na wykresie BoxAndWhisker. Dotyczy wyłącznie wykresów BoxAndWhisker. Odczyt/zapis Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Reprezentuje wygładzanie krzywej. Prawda, jeśli wygładzanie krzywej jest włączone dla wykresu liniowego lub wykresu punktowego. Dotyczy wyłącznie wykresów liniowych i punktowych połączonych liniami. Odczyt/zapis Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Kolekcja linii trendu serii. Tylko do odczytu [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Zwraca typ tej serii. Odczyt/zapis [`ChartType`](../charttype). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Zwraca automatyczny kolor serii na podstawie indeksu serii i stylu wykresu. Ten kolor jest używany domyślnie, jeśli FillType jest równy NotDefined. |

### Zobacz także

* interfejs [IChartSeries](../ichartseries)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->