---
title: InsertChart()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový graf, inicializuje jej vzorovými daty řad a nastaveními a vloží jej do kolekce tvarů na zadaném indexu.
type: docs
weight: 92
url: /cs/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) metoda

Vytvoří nový graf, inicializuje jej vzorovými daty řad a nastaveními a vloží jej do kolekce tvarů na zadaném indexu.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ grafu, který se má vytvořit. |
| x | **float** | X-souřadnice nového grafu v bodech. |
| y | **float** | Y-souřadnice nového grafu v bodech. |
| width | **float** | Šířka nového grafu v bodech. |
| height | **float** | Výška nového grafu v bodech. |
| index | **int32_t** | Nulový index, na který se má nový graf vložit do kolekce tvarů. |

### Návratová hodnota

Nově vytvořený [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) metoda

Vytvoří nový graf, inicializuje jej vzorovými daty řad a nastaveními a vloží jej do kolekce tvarů na zadaném indexu.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ grafu, který se má vytvořit. |
| x | **float** | X-souřadnice nového grafu v bodech. |
| y | **float** | Y-souřadnice nového grafu v bodech. |
| width | **float** | Šířka nového grafu v bodech. |
| height | **float** | Výška nového grafu v bodech. |
| index | **int32_t** | Nulový index, na který se má nový graf vložit do kolekce tvarů. |
| initWithSample | **bool** | True pro inicializaci nového grafu vzorovými daty řad a nastaveními; false pro vytvoření grafu bez řad a pouze s minimálními nastaveními, což urychluje vytvoření. |

### Návratová hodnota

Nově vytvořený [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Viz také

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChart](../../../aspose.slides.charts/ichart/)
* Třída [ShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)