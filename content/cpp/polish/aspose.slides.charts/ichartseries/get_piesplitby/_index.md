---
title: get_PieSplitBy()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Określa, jak ustalić, które punkty danych znajdują się w drugim kawałku lub słupku wykresu typu pie-of-pie lub bar-of-pie. Jest to własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej - jest to projekcja odpowiedniej własności grupy. Dlatego ta własność jest tylko do odczytu. Użyj własności ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj get_ParentSeriesGroup()->get(set)_PieSplitBy() własności odczyt/zapis, aby zmienić wartość. Tylko do odczytu PieSplitType.
type: docs
weight: 729
url: /pl/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() metoda


Określa, jak ustalić, które punkty danych znajdują się w drugim kawałku lub słupku wykresu pie-of-pie lub bar-of-pie. Jest to własność nie tylko tej serii, ale wszystkich serii grupy serii nadrzędnej – jest to projekcja odpowiedniej właściwości grupy. Dlatego ta właściwość jest tylko do odczytu. Użyj właściwości ParentSeriesGroup, aby uzyskać dostęp do grupy serii nadrzędnej. Użyj [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() właściwości odczyt/zapis, aby zmienić wartość. Tylko do odczytu [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Uwagi


1) Jest to projekcja własności [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Jeśli wartość własności wynosi [PieSplitType::Custom](../../piesplittype/), możesz określić własne informacje o podziale przy użyciu własności [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/). 
## Zobacz także

* Wyliczenie [PieSplitType](../../piesplittype/)
* Klasa [IChartSeries](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)