---
title: InsertChart()
second_title: Aspose.Slides pro C++ - referenční API
description: Vytvoří nový graf, inicializuje jej ukázkovými daty řady a nastaveními a vloží jej do kolekce tvarů na zadaném indexu.
type: docs
weight: 53
url: /cs/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) metoda

Vytvoří nový graf, inicializuje jej ukázkovými daty řady a nastaveními a vloží jej do kolekce tvarů na zadaném indexu.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ grafu, který se má vytvořit. |
| x | **float** | Souřadnice x nového grafu v bodech. |
| y | **float** | Souřadnice y nového grafu v bodech. |
| width | **float** | Šířka nového grafu v bodech. |
| height | **float** | Výška nového grafu v bodech. |
| index | **int32_t** | Nulový index, na který se má nový graf vložit do kolekce tvarů. |

### Návratová hodnota

Nově vytvořený [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) metoda

Vytvoří nový graf, inicializuje jej ukázkovými daty řady a nastaveními a vloží jej do kolekce tvarů na zadaném indexu.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Typ grafu, který se má vytvořit. |
| x | **float** | Souřadnice x nového grafu v bodech. |
| y | **float** | Souřadnice y nového grafu v bodech. |
| width | **float** | Šířka nového grafu v bodech. |
| height | **float** | Výška nového grafu v bodech. |
| index | **int32_t** | Nulový index, na který se má nový graf vložit do kolekce tvarů. |
| initWithSample | **bool** | True, pokud chcete inicializovat nový graf ukázkovými daty řady a nastaveními; false, pokud chcete vytvořit graf bez řad a pouze s minimálními nastaveními, což urychluje vytvoření. |

### Návratová hodnota

Nově vytvořený [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Viz také

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)