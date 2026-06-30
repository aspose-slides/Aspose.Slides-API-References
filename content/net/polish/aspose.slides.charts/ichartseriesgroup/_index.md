---
title: IChartSeriesGroup
second_title: Aspose.Slides dla .NET – odniesienie API
description: Reprezentuje grupę serii.
type: docs
weight: 1930
url: /pl/aspose.slides.charts/ichartseriesgroup/
---
## Interfejs IChartSeriesGroup

Reprezentuje grupę serii.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Umożliwia pobranie podstawowego interfejsu IChartComponent. Tylko do odczytu [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Określa, w jaki sposób wartości rozmiaru bąbelka są reprezentowane na wykresie bąbelkowym. Odczyt/zapis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Określa współczynnik skalowania wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Odczyt/zapis Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). Odczyt/zapis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Odczyt/zapis UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Zwraca lub ustawia odległość, wyrażoną jako procent szerokości znacznika, pomiędzy seriami danych w wykresie 3D. Odczyt/zapis UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Określa odstęp pomiędzy grupami słupków lub kolumn, wyrażony jako procent szerokości słupka lub kolumny. Odczyt/zapis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True, jeśli wykres ma linie serii. Zastosowane do wykresów słupkowych skumulowanych i OfPie. Odczyt/zapis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Określa format HiLowLines. HiLowLines stosowane z typami wykresów HiLowClose, OpenHiLowClose, VolumeHiLowClose i VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Określa, że każdy znacznik danych w serii ma inny kolor. Odczyt/zapis Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Pobiera element o podanym indeksie. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Określa, jak bardzo słupki i kolumny mają nachodzić na wykresach 2-D, wyrażone jako procent (od -100 % do 100 %). -100 %: maksymalny odstęp (słupki całkowicie oddzielone). 0 %: słupki ustawione obok siebie bez nachodzenia i bez odstępu. 100 %: maksymalne nachodzenie (słupki całkowicie na siebie nachodzą). Ta własność jest odczyt/zapis SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Określa, w jaki sposób określić, które punkty danych znajdują się w drugim wykresie kołowym lub słupkowym wykresu pie-of-pie lub bar-of-pie. Odczyt/zapis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Niestandardowe informacje o podziale dla wykresu pie-of-pie lub bar-of-pie z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim wykresie kołowym lub słupkowym. Tylko do odczytu [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Określa wartość używaną do określenia, które punkty danych znajdują się w drugim wykresie kołowym lub słupkowym wykresu pie-of-pie lub bar-of-pie. Używana razem z właściwością PieSplitBy. Odczyt/zapis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Wskazuje, czy serie w tej grupie są rysowane na dodatkowej osi. Tylko do odczytu Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Określa rozmiar drugiego wykresu kołowego lub słupkowego wykresu pie-of-pie lub bar-of-pie, wyrażony jako procent rozmiaru pierwszego wykresu kołowego (może wynosić od 5 do 200 procent). Odczyt/zapis UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Zwraca kolekcję serii wykresu do odczytu. Tylko do odczytu [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Zwraca typ tej grupy serii. Tylko do odczytu [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Zapewnia dostęp do pasków górnych/dolnych wykresu liniowego lub giełdowego. Tylko do odczytu [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Uwagi

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection oraz wyliczenia CombinableSeriesTypesGroup.  
2) Grupa serii zawiera pewne właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”). „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis. Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

### Zobacz także

* interface [IChartComponent](../ichartcomponent)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->