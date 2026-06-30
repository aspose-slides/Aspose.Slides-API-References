---
title: ChartSeriesGroup
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Reprezentuje grupę serii.
type: docs
weight: 1440
url: /pl/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klasa

Represents group of series.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. Odczyt/zapis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Określa współczynnik skalowania dla wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Odczyt/zapis Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Zwraca wykres nadrzędny. Tylko do odczytu [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procent rozmiaru obszaru wykresu). Odczyt/zapis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Odczyt/zapis UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Zwraca lub ustawia odległość, jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. Odczyt/zapis UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Określa odstęp między grupami słupków lub kolumn, jako procent szerokości słupka lub kolumny. Odczyt/zapis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True, jeśli wykres ma linie serii. Stosowane w wykresach słupkowych skumulowanych oraz OfPie. Odczyt/zapis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Określa format HiLowLines. HiLowLines jest stosowane z typami wykresów HiLowClose, OpenHiLowClose, VolumeHiLowClose i VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Określa, że każdy znacznik danych w serii ma inny kolor. Odczyt/zapis Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Pobiera element o określonym indeksie. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Określa, w jakim stopniu słupki i kolumny będą zachodzić na siebie w wykresach 2D, jako procent (od -100% do 100%). - -100%: maksymalny odstęp (słupki są całkowicie oddzielone). - 0%: słupki są ustawione obok siebie bez zachodzenia ani odstępu. - 100%: maksymalne zachodzenie (słupki całkowicie na siebie zachodzą). Ta właściwość jest odczyt/zapis SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Określa, jak określić, które punkty danych znajdują się w drugim wykresie kołowym lub słupkowym w wykresie pie-of-pie lub bar-of-pie. Odczyt/zapis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Informacje o niestandardowym podziale dla wykresu pie-of-pie lub bar-of-pie z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim wykresie kołowym lub słupkowym w wykresie pie-of-pie lub bar-of-pie. Tylko do odczytu [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Określa wartość, która ma być użyta do określenia, które punkty danych znajdują się w drugim wykresie kołowym lub słupkowym w wykresie pie-of-pie lub bar-of-pie. Jest używana razem z właściwością PieSplitBy. Odczyt/zapis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Wskazuje, czy serie tej grupy są wykreślone na drugiej osi. Tylko do odczytu Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Określa rozmiar drugiego wykresu kołowego lub słupkowego w wykresie pie-of-pie lub bar-of-pie, jako procent rozmiaru pierwszego wykresu (może wynosić od 5 do 200 procent). Odczyt/zapis UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Zwraca kolekcję serii. Tylko do odczytu [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Zwraca typ tej grupy serii. Tylko do odczytu [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Zapewnia dostęp do pasków góra/dół wykresu liniowego lub giełdowego. Tylko do odczytu [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Uwagi

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection oraz wyliczenia CombinableSeriesTypesGroup. 2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie ("series group properties"). "Series group properties" w klasie ChartSeriesGroup są odczyt/zapis. Każda z "series group properties" może mieć projekcję tylko do odczytu w klasie ChartSeries.

### Zobacz także

* interfejs [IChartSeriesGroup](../ichartseriesgroup)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->