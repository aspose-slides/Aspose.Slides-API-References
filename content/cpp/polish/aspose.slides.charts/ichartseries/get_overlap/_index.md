---
title: get_Overlap()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa, o ile słupki i kolumny zachodzą na siebie na wykresach 2-D, wyrażone jako procent (od -100% do 100%). Jest to właściwość nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnej. To projekcja odpowiedniej właściwości w grupie serii nadrzędnej, dlatego ta właściwość jest tylko do odczytu. Aby zmienić wartość, użyj właściwości odczyt/zapis get_ParentSeriesGroup()->get(set)_Overlap() read/write property. Read-only int8_t.
type: docs
weight: 690
url: /pl/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() metoda

Określa, o ile słupki i kolumny zachodzą na siebie na wykresach 2-D, wyrażone jako procent (od -100% do 100%). To nie jest właściwość tylko tej serii, ale wszystkich serii w grupie serii nadrzędnej. Jest to projekcja odpowiedniej właściwości w grupie serii nadrzędnej, dlatego ta właściwość jest tylko do odczytu. Aby zmienić wartość, użyj [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() właściwości odczyt/zapis. Tylko do odczytu **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Uwagi

Overlap określa stopień zachodzenia lub odstępu między słupkami i kolumnami jako procent ich szerokości:
* -100%: Maksymalny odstęp (słupki są całkowicie oddzielone).
* 0%: Słupki są umieszczone obok siebie bez zachodzenia ani odstępu.
* 100%: Maksymalne zachodzenie (słupki całkowicie na siebie zachodzą). Jest to projekcja właściwości [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap().

## Zobacz także

* Klasa [IChartSeries](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)