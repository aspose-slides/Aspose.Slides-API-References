---
title: AddChart()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami, a następnie dodaje go na koniec kolekcji kształtów.
type: docs
weight: 27
url: /pl/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) metoda

Tworzy nowy wykres, inicjalizuje go danymi przykładowej serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ wykresu do dodania. |
| x | **float** | Współrzędna x nowego wykresu, w punktach. |
| y | **float** | Współrzędna y nowego wykresu, w punktach. |
| width | **float** | Szerokość wykresu, w punktach. |
| height | **float** | Wysokość wykresu, w punktach. |

### Wartość zwracana

Nowo utworzony [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) metoda

Tworzy nowy wykres, inicjalizuje go danymi przykładowej serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ wykresu do dodania. |
| x | **float** | Współrzędna x nowego wykresu, w punktach. |
| y | **float** | Współrzędna y nowego wykresu, w punktach. |
| width | **float** | Szerokość wykresu, w punktach. |
| height | **float** | Wysokość wykresu, w punktach. |
| initWithSample | **bool** | True to initialize the new chart with sample series data and settings; false to create the chart with no series and only minimal settings, which makes creation faster. |

### Wartość zwracana

Nowo utworzony [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Zobacz także

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChart](../../../aspose.slides.charts/ichart/)
* Klasa [IShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)