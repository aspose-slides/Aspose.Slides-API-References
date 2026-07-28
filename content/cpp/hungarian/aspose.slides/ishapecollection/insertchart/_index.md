---
title: InsertChart()
second_title: Aspose.Slides for C++ API Referenciája
description: Új diagramot hoz létre, mintasorozati adatokkal és beállításokkal inicializálja, és a megadott indexnél beszúrja az alakzatgyűjteménybe.
type: docs
weight: 53
url: /hu/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) metódus

Létrehoz egy új diagramot, inicializálja mintasorozat adatokkal és beállításokkal, és beszúrája a alakzatgyűjteménybe a megadott indexnél.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | A létrehozandó diagram típusa. |
| x | **float** | Az új diagram x-koordinátája pontban. |
| y | **float** | Az új diagram y-koordinátája pontban. |
| width | **float** | Az új diagram szélessége pontban. |
| height | **float** | Az új diagram magassága pontban. |
| index | **int32_t** | Az a nullaalapú index, amelynél az új diagramot be kell szúrni az alakzatgyűjteménybe. |

### Visszatérési érték

A frissen létrehozott [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) metódus

Létrehoz egy új diagramot, inicializálja mintasorozat adatokkal és beállításokkal, és beszúrája a alakzatgyűjteménybe a megadott indexnél.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | A létrehozandó diagram típusa. |
| x | **float** | Az új diagram x-koordinátája pontban. |
| y | **float** | Az új diagram y-koordinátája pontban. |
| width | **float** | Az új diagram szélessége pontban. |
| height | **float** | Az új diagram magassága pontban. |
| index | **int32_t** | Az a nullaalapú index, amelynél az új diagramot be kell szúrni az alakzatgyűjteménybe. |
| initWithSample | **bool** | Igaz, ha a új diagramot mintasorozat adatokkal és beállításokkal szeretné inicializálni; hamis, ha a diagramot sorozat nélkül és csak minimális beállításokkal hozza létre, ami gyorsabbá teszi a létrehozást. |

### Visszatérési érték

A frissen létrehozott [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Lásd még

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChart](../../../aspose.slides.charts/ichart/)
* Osztály [IShapeCollection](../)
* Névtere [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)