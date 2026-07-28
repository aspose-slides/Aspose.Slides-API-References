---
title: InsertChart()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehoz egy új diagramot, mintasorozat-adatokkal és beállításokkal inicializálja, majd a megadott indexnél beszúrja a shape collection-be.
type: docs
weight: 92
url: /hu/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) metódus


Létrehoz egy új diagramot, mintasorozat-adatokkal és beállításokkal inicializálja, majd a megadott indexnél beszúrja a shape collection-be.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | A létrehozandó diagram típusa. |
| x | **float** | Az új diagram x-koordinátája pontban. |
| y | **float** | Az új diagram y-koordinátája pontban. |
| width | **float** | Az új diagram szélessége pontban. |
| height | **float** | Az új diagram magassága pontban. |
| index | **int32_t** | Az a nullától kezdődő index, amelyen az új diagramot a shape collection-be kell beszúrni. |

### Visszatérési érték

Az újonnan létrehozott [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) metódus


Létrehoz egy új diagramot, mintasorozat-adatokkal és beállításokkal inicializálja, majd a megadott indexnél beszúrja a shape collection-be.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | A létrehozandó diagram típusa. |
| x | **float** | Az új diagram x-koordinátája pontban. |
| y | **float** | Az új diagram y-koordinátája pontban. |
| width | **float** | Az új diagram szélessége pontban. |
| height | **float** | Az új diagram magassága pontban. |
| index | **int32_t** | Az a nullától kezdődő index, amelyen az új diagramot a shape collection-be kell beszúrni. |
| initWithSample | **bool** | Igaz, ha az új diagramot mintasorozat-adatokkal és beállításokkal kell inicializálni; hamis, ha a diagramot sorozat nélkül és csak minimális beállításokkal hozza létre, ami gyorsabb. |

### Visszatérési érték

Az újonnan létrehozott [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Lásd még

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChart](../../../aspose.slides.charts/ichart/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)