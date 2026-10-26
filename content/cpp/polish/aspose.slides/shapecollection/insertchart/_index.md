---
title: InsertChart()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów pod wskazanym indeksem.
type: docs
weight: 92
url: /pl/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) metoda

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów pod podanym indeksem.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ wykresu do utworzenia. |
| x | **float** | Współrzędna x nowego wykresu, w punktach. |
| y | **float** | Współrzędna y nowego wykresu, w punktach. |
| width | **float** | Szerokość nowego wykresu, w punktach. |
| height | **float** | Wysokość nowego wykresu, w punktach. |
| index | **int32_t** | Indeks zerowy, pod którym wstawia się nowy wykres w kolekcji kształtów. |

### Wartość zwracana

Nowo utworzony [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) metoda

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów pod podanym indeksem.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ wykresu do utworzenia. |
| x | **float** | Współrzędna x nowego wykresu, w punktach. |
| y | **float** | Współrzędna y nowego wykresu, w punktach. |
| width | **float** | Szerokość nowego wykresu, w punktach. |
| height | **float** | Wysokość nowego wykresu, w punktach. |
| index | **int32_t** | Indeks zerowy, pod którym wstawia się nowy wykres w kolekcji kształtów. |
| initWithSample | **bool** | Prawda, aby zainicjować nowy wykres danymi i ustawieniami przykładowych serii; fałsz, aby utworzyć wykres bez serii i jedynie z minimalnymi ustawieniami, co przyspiesza tworzenie. |

### Wartość zwracana

Nowo utworzony [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Zobacz także

* Wyliczenie [ChartType](../../../aspose.slides.charts/charttype/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IChart](../../../aspose.slides.charts/ichart/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)