---
title: ChartSeriesGroup
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Reprezentuje grupę serii.
type: docs
weight: 1460
url: /pl/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klasa

Reprezentuje grupę serii.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Określa, jak wartości rozmiaru bąbelka są przedstawiane na wykresie bąbelkowym. Odczyt/zapis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Określa współczynnik skali wykresu bąbelkowego (może wynosić od 0 do 300 procentów domyślnego rozmiaru). Odczyt/zapis Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Zwraca nadrzędny wykres. Tylko do odczytu [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 0 do 90 procentów rozmiaru obszaru wykresu). Odczyt/zapis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Pobiera lub ustawia kąt pierwszego segmentu wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Odczyt/zapis UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Zwraca lub ustawia odległość, wyrażoną w procentach szerokości znacznika, pomiędzy seriami danych w wykresie 3D. Odczyt/zapis UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Określa odstęp między grupami słupków lub kolumn, wyrażony w procentach ich szerokości. Odczyt/zapis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Prawda, jeśli wykres zawiera linie serii. Zastosowane do wykresów słupkowych skumulowanych i OfPie. Odczyt/zapis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Określa format HiLowLines. HiLowLines stosowane z typami wykresów HiLowClose, OpenHiLowClose, VolumeHiLowClose oraz VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Określa, że każdy znacznik danych w serii ma inny kolor. Odczyt/zapis Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Pobiera element o podanym indeksie. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Określa, o ile słupki i kolumny mają nachodzić na wykresach 2-D, wyrażone w procentach (od -100 % do 100 %). -100 %: maksymalne odstępy (słupki całkowicie rozdzielone). 0 %: słupki umieszczone obok siebie bez nachodzenia i bez odstępów. 100 %: maksymalne nachodzenie (słupki całkowicie na siebie nachodzą). Ta właściwość jest odczyt/zapis SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Określa, jak określić, które punkty danych znajdują się w drugim wykresie kołowym lub słupkowym wykresu pie-of-pie lub bar-of-pie. Odczyt/zapis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Niestandardowe informacje o podziale dla wykresu pie-of-pie lub bar-of-pie z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim wykresie kołowym lub słupkowym. Tylko do odczytu [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim wykresie kołowym lub słupkowym wykresu pie-of-pie lub bar-of-pie. Używana razem z właściwością PieSplitBy. Odczyt/zapis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Wskazuje, czy serie tej grupy są wykreślane na drugiej osi. Tylko do odczytu Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Określa rozmiar drugiego wykresu kołowego lub słupkowego wykresu pie-of-pie lub bar-of-pie, wyrażony w procentach rozmiaru pierwszego wykresu (może wynosić od 5 do 200 procentów). Odczyt/zapis UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Zwraca kolekcję serii. Tylko do odczytu [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Zwraca typ tej grupy serii. Tylko do odczytu [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Zapewnia dostęp do pasków górnych/dolnych wykresu liniowego lub giełdowego. Tylko do odczytu [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Uwagi

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection oraz wyliczenia CombinableSeriesTypesGroup enum.  
2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”). „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis. Każda z „właściwości grupy serii” może mieć tylko do odczytu projekcję w klasie ChartSeries.

### Zobacz też

* interfejs [IChartSeriesGroup](../ichartseriesgroup)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->