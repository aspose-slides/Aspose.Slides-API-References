---
title: AddChart()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními a přidá jej na konec kolekce tvarů.
type: docs
weight: 27
url: /cs/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) metoda


Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ grafu, který se má přidat. |
| x | **float** | Souřadnice x nového grafu v bodech. |
| y | **float** | Souřadnice y nového grafu v bodech. |
| width | **float** | Šířka grafu v bodech. |
| height | **float** | Výška grafu v bodech. |

### Návratová hodnota

Nově vytvořený [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) metoda


Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními a přidá jej na konec kolekce tvarů.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ grafu, který se má přidat. |
| x | **float** | Souřadnice x nového grafu v bodech. |
| y | **float** | Souřadnice y nového grafu v bodech. |
| width | **float** | Šířka grafu v bodech. |
| height | **float** | Výška grafu v bodech. |
| initWithSample | **bool** | True to initialize the new chart with sample series data and settings; false to create the chart with no series and only minimal settings, which makes creation faster. |

### Návratová hodnota

Nově vytvořený [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Viz také

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChart](../../../aspose.slides.charts/ichart/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)