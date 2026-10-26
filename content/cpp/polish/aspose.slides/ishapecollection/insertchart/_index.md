---
title: InsertChart()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów w określonym indeksie.
type: docs
weight: 53
url: /pl/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) method

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów w określonym indeksie.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ wykresu do utworzenia. |
| x | **float** | Współrzędna x nowego wykresu, w punktach. |
| y | **float** | Współrzędna y nowego wykresu, w punktach. |
| width | **float** | Szerokość nowego wykresu, w punktach. |
| height | **float** | Wysokość nowego wykresu, w punktach. |
| index | **int32_t** | Indeks zerowy, w którym wstawić nowy wykres w kolekcji kształtów. |

### Wartość zwracana

Nowo utworzony [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) method

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów w określonym indeksie.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ wykresu do utworzenia. |
| x | **float** | Współrzędna x nowego wykresu, w punktach. |
| y | **float** | Współrzędna y nowego wykresu, w punktach. |
| width | **float** | Szerokość nowego wykresu, w punktach. |
| height | **float** | Wysokość nowego wykresu, w punktach. |
| index | **int32_t** | Indeks zerowy, w którym wstawić nowy wykres w kolekcji kształtów. |
| initWithSample | **bool** | Prawda, aby zainicjować nowy wykres przykładowymi danymi serii i ustawieniami; fałsz, aby utworzyć wykres bez serii i tylko z minimalnymi ustawieniami, co przyspiesza tworzenie. |

### Wartość zwracana

Nowo utworzony [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Zobacz także

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)