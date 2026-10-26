---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Jeśli kolekcja już zawiera punkt danych o indeksie index, wtedy zwraca ten punkt danych. Jeśli kolekcja nie zawiera punktu danych o indeksie index ==N (gdy liczba punktów danych w tej kolekcji jest mniejsza lub równa N), wtedy dodaje brakujące punkty danych i zwraca ostatni (który ma żądany indeks). Na przykład, indeksy kolekcji to {0, 1, 2}, a żądany indeks to 5. Wtedy metoda dodaje brakujące punkty danych: {0, 1, 2, 3, 4, 5}. I zwraca punkt danych o indeksie 5."
type: docs
weight: 170
url: /pl/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) metoda

Jeśli kolekcja już zawiera punkt danych o indeksie *index*, to zwraca ten punkt danych. Jeśli kolekcja nie zawiera punktu danych o indeksie *index* ==N (gdy liczba punktów danych w tej kolekcji jest mniejsza lub równa N), to dodaje brakujące punkty danych i zwraca ostatni (który ma żądany indeks). Na przykład, indeksy kolekcji to {0, 1, 2}, a żądany indeks to 5. Wtedy metoda dodaje brakujące punkty danych: {0, 1, 2, 3, 4, 5}. I zwraca punkt danych o indeksie 5.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **uint32_t** | Indeks. |

### Wartość zwracana

Zwraca punkt danych o żądanym indeksie.

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartDataPoint](../../ichartdatapoint/)
* Klasa [ChartDataPointCollection](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)