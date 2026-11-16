---
title: IChartSeriesGroup
second_title: Aspose.Sildes dla .NET - dokumentacja API
description: Reprezentuje grupę serii.
type: docs
weight: 1970
url: /pl/aspose.slides.charts/ichartseriesgroup/
---
## Interfejs IChartSeriesGroup

Reprezentuje grupę serii.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Właściwości

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Umożliwia uzyskanie podstawowego interfejsu IChartComponent. Tylko do odczytu [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Określa, jak wartości rozmiaru bąbelków są reprezentowane na wykresie bąbelkowym. Odczyt/zapis [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Określa współczynnik skalowania dla wykresu bąbelkowego (może wynosić od 0 do 300 procent domyślnego rozmiaru). Odczyt/zapis Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Określa rozmiar otworu w wykresie pierścieniowym (może wynosić od 10 do 90 procent rozmiaru obszaru wykresu). Odczyt/zapis Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Pobiera lub ustawia kąt pierwszego wycinka wykresu kołowego lub pierścieniowego, w stopniach (zgodnie z ruchem wskazówek zegara od góry, od 0 do 360 stopni). Odczyt/zapis UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Pobiera lub ustawia odległość między seriami danych w wykresie 3D, wyrażoną jako procent szerokości znacznika. Wartość musi wynosić od 0 do 500. Odczyt/zapis UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Pobiera lub ustawia odstęp między grupami słupków lub kolumn, wyrażony jako procent szerokości słupka lub kolumny. Wartość musi wynosić od 0 do 500. Odczyt/zapis UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Prawda, jeśli wykres ma linie serii. Zastosowane do wykresów słupkowych skumulowanych i OfPie. Odczyt/zapis Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Określa format HiLowLines. HiLowLines stosowane z typami wykresów HiLowClose, OpenHiLowClose, VolumeHiLowClose i VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Określa, że każdy znacznik danych w serii ma inny kolor. Odczyt/zapis Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Pobiera element o podanym indeksie. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Określa, jak bardzo słupki i kolumny mają nachodzić na wykresach 2D, wyrażone jako procent (od -100% do 100%). - -100%: maksymalny odstęp (słupki są całkowicie oddzielone). - 0%: słupki są ustawione obok siebie bez nachodzenia ani odstępu. - 100%: maksymalne nachodzenie (słupki całkowicie na siebie nachodzą). Ta własność jest odczyt/zapis SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Określa, jak ustalić, które punkty danych znajdują się w drugim wycinku lub słupku wykresu pie-of-pie lub bar-of-pie. Odczyt/zapis [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Niestandardowe informacje o podziale dla wykresu pie-of-pie lub bar-of-pie z niestandardowym podziałem. Zawiera punkty danych, które mają być rysowane w drugim wycinku lub słupku wykresu pie-of-pie lub bar-of-pie. Tylko do odczytu [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Określa wartość, która ma być użyta do określenia, które punkty danych znajdują się w drugim wycinku lub słupku wykresu pie-of-pie lub bar-of-pie. Używana razem z właściwością PieSplitBy. Odczyt/zapis Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Wskazuje, czy serie tej grupy są wykreślone na osi drugorzędnej. Tylko do odczytu Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Określa rozmiar drugiego wycinka lub słupka wykresu pie-of-pie lub bar-of-pie, wyrażony jako procent rozmiaru pierwszego wycinka (może wynosić od 5 do 200 procent). Odczyt/zapis UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Zwraca kolekcję serii wykresu tylko do odczytu. Tylko do odczytu [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Zwraca typ tej grupy serii. Tylko do odczytu [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Zapewnia dostęp do słupków górnych/dolnych wykresu liniowego lub giełdowego. Tylko do odczytu [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Uwagi

1) Zobacz podsumowanie i uwagi dla klasy ChartSeriesGroupCollection oraz wyliczenia CombinableSeriesTypesGroup. 2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”). „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis. Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

### Zobacz także

* interfejs [IChartComponent](../ichartcomponent)
* przestrzeń nazw [Aspose.Slides.Charts](../../aspose.slides.charts)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->