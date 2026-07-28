---
title: Remove()
second_title: Aspose.Slides dla C++ Referencja API
description: Usuwa element z kolekcji.
type: docs
weight: 79
url: /pl/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) metoda


Usuwa element z kolekcji.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Punkt danych do usunięcia. |

### Wartość zwracana

true, jeśli element został pomyślnie usunięty; w przeciwnym razie false. Metoda ta zwraca również false, jeśli element nie został znaleziony w [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) metoda


Usuwa element z kolekcji według jego indeksu w kolekcji punktów serii nadrzędnej.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Indeks punktu danych w kolekcji punktów serii nadrzędnej. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChartDataPoint](../../ichartdatapoint/)
* Klasa [PieSplitCustomPointCollection](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)