---
title: get_PieSplitBy()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, jak określić, które punkty danych znajdują się w drugim kawałku lub słupku wykresu typu pie-of-pie lub bar-of-pie. Jest to własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej własności grupy. W związku z tym własność ta jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj get_ParentSeriesGroup()->get(set)_PieSplitBy() własności odczyt/zapis, aby zmienić wartość. Tylko do odczytu PieSplitType.
type: docs
weight: 755
url: /pl/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() metoda

Określa, jak określić, które punkty danych znajdują się w drugim kawałku lub słupku wykresu typu pie-of-pie lub bar-of-pie. Jest to własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej własności grupy. W związku z tym własność ta jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() własności odczyt/zapis, aby zmienić wartość. Tylko do odczytu [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Uwagi

1) Jest to projekcja własności [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Jeśli wartość własności wynosi [PieSplitType::Custom](../../piesplittype/), możesz zdefiniować własne informacje podziału przy użyciu własności [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Zobacz też

* Enum [PieSplitType](../../piesplittype/)
* Klasa [ChartSeries](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)