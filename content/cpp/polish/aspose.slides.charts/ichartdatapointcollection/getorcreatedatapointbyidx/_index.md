---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Jeśli kolekcja już zawiera punkt danych o indeksie index, metoda zwraca ten punkt danych. Jeśli kolekcja nie zawiera punktu danych o indeksie index ==N (gdy liczba punktów danych w tej kolekcji jest mniejsza lub równa N), metoda dodaje brakujące punkty danych i zwraca ostatni (który ma żądany indeks). Na przykład, indeksy w kolekcji to {0, 1, 2}, a żądany indeks to 5. Wtedy metoda dodaje brakujące punkty danych: {0, 1, 2, 3, 4, 5}. i zwraca punkt danych o indeksie 5."
type: docs
weight: 131
url: /pl/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) metoda


If collection already contains data point with index *index*  then returns this data point. If collection doesn't contains data point with index *index* ==N (when number of data points in this collection is less or equal then N) then adds deficient data points and returns last (which has requested index). For example, collection indexes are {0, 1, 2}, and requested index is 5. Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **uint32_t** | Indeks. |

### Wartość zwracana

Zwraca punkt danych z żądanym indeksem.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartDataPoint](../../ichartdatapoint/)
* Klasa [IChartDataPointCollection](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)