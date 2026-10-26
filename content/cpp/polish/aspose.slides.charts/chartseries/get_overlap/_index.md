---
title: get_Overlap()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa, w jakim stopniu słupki i kolumny nachodzą na siebie na wykresach 2-D, wyrażone w procentach (od -100% do 100%). Jest to własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnej. Jest to projekcja odpowiedniej własności w grupie serii nadrzędnej, dlatego własność ta jest tylko do odczytu. Aby zmienić wartość, użyj własności odczyt/zapis get_ParentSeriesGroup()->Overlap(). Tylko do odczytu int8_t.
type: docs
weight: 690
url: /pl/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() metoda


Określa, o ile słupki i kolumny zachodzą na siebie na wykresach 2-D, wyrażone w procentach (od -100% do 100%). To jest własność nie tylko tej serii, ale wszystkich serii w grupie serii nadrzędnej. Jest to projekcja odpowiedniej własności w grupie serii nadrzędnej, dlatego własność ta jest tylko do odczytu. Aby zmienić wartość, użyj własności [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) odczyt/zapis. Tylko do odczytu **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## Uwagi


Overlap określa stopień nachodzenia lub odstępu między słupkami i kolumnami jako procent ich szerokości:
* -100%: Maksymalne odstępy (słupki są całkowicie rozdzielone).
* 0%: Słupki są ustawione obok siebie bez nachodzenia i bez odstępu.
* 100%: Maksymalne nachodzenie (słupki całkowicie zachodzą na siebie). Jest to projekcja własności [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/).


## Zobacz także

* Class [ChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)