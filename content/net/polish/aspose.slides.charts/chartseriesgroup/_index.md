---
title: ChartSeriesGroup
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje grupę serii.
type: docs
weight: 1470
url: /pl/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klasa

Reprezentuje grupę serii.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Właściwości

| Name | Description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Określa, w jaki sposób wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. Odczyt/zapis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Określa współczynnik skali wykresu bąbelkowego (może wynosić od 0 do 300 % domyślnego rozmiaru). Odczyt/zapis Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Zwraca wykres nadrzędny. Tylko do odczytu [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 % rozmiaru obszaru wykresu). Odczyt/zapis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Odczyt/zapis UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Pobiera lub ustawia odległość między seriami danych w wykresie 3D, wyrażoną jako procent szerokości znacznika. Wartość musi mieścić się w przedziale od 0 do 500. Odczyt/zapis UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Pobiera lub ustawia odstęp między grupami słupków lub kolumn, wyrażony jako procent ich szerokości. Wartość musi mieścić się w przedziale od 0 do 500. Odczyt/zapis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Prawda, jeśli wykres ma linie serii. Zastosowane do wykresów słupkowych skumulowanych i OfPie. Odczyt/zapis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Określa format HiLowLines. HiLowLines stosowane w typach wykresów HiLowClose, OpenHiLowClose, VolumeHiLowClose i VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Określa, że każdy znacznik danych w serii ma inny kolor. Odczyt/zapis Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Pobiera element o podanym indeksie. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Określa, jak bardzo słupki i kolumny mają się na siebie nakładać na wykresach 2-D, wyrażone jako procent (od –100 % do 100 %). – –100 %: maksymalne rozstawienie (słupki są całkowicie oddzielone). – 0 %: słupki są ustawione obok siebie bez nakładania się i bez przerw. – 100 %: maksymalne nakładanie się (słupki całkowicie na siebie nachodzą). Właściwość jest odczyt/zapis SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Określa, w jaki sposób ustala się, które punkty danych znajdują się w drugim wycinku wykresu kołowego lub słupkowego w wykresie typu pie-of-pie lub bar-of-pie. Odczyt/zapis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Informacje o własnym podziale dla wykresu typu pie-of-pie lub bar-of-pie z własnym podziałem. Zawiera punkty danych, które mają być rysowane w drugim wycinku wykresu. Tylko do odczytu [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim wycinku wykresu typu pie-of-pie lub bar-of-pie. Stosowane razem z właściwością PieSplitBy. Odczyt/zapis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Wskazuje, czy serie tej grupy są rysowane na pomocniczej osi. Tylko do odczytu Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Określa rozmiar drugiego wycinka wykresu typu pie-of-pie lub bar-of-pie, wyrażony jako procent rozmiaru pierwszego wycinka (może wynosić od 5 do 200 %). Odczyt/zapis UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Zwraca kolekcję serii. Tylko do odczytu [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Zwraca typ tej grupy serii. Tylko do odczytu [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Zapewnia dostęp do słupków górnych/dolnych wykresu liniowego lub giełdowego. Tylko do odczytu [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Uwagi

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection i wyliczenia CombinableSeriesTypesGroup. 2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”). „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis. Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

### Zobacz także

* interfejs [IChartSeriesGroup](../ichartseriesgroup)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->