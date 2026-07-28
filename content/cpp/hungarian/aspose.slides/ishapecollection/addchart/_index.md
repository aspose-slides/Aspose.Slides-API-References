---
title: AddChart()
second_title: Aspose.Slides C++ API referenciája
description: Új diagramot hoz létre, minta sorozatadatokkal és beállításokkal inicializálja, majd a alakzatgyűjtemény végére adja hozzá.
type: docs
weight: 27
url: /hu/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) metódus

Új diagramot hoz létre, minta sorozatadatokkal és beállításokkal inicializálja, majd a alakzatgyűjtemény végére adja hozzá.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | A hozzáadandó diagram típusa. |
| x | **float** | Az új diagram x-koordinátája pontokban. |
| y | **float** | Az új diagram y-koordinátája pontokban. |
| width | **float** | A diagram szélessége pontokban. |
| height | **float** | A diagram magassága pontokban. |

### Visszatérési érték

Az újonnan létrehozott [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) metódus

Új diagramot hoz létre, minta sorozatadatokkal és beállításokkal inicializálja, majd a alakzatgyűjtemény végére adja hozzá.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | A hozzáadandó diagram típusa. |
| x | **float** | Az új diagram x-koordinátája pontokban. |
| y | **float** | Az új diagram y-koordinátája pontokban. |
| width | **float** | A diagram szélessége pontokban. |
| height | **float** | A diagram magassága pontokban. |
| initWithSample | **bool** | Igaz, ha az új diagramot minta sorozatadatokkal és beállításokkal inicializálni szeretné; hamis, ha a diagramot sorozat nélkül és csak minimális beállításokkal hozza létre, ami gyorsabbá teszi a létrehozást. |

### Visszatérési érték

Az újonnan létrehozott [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Lásd még

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChart](../../../aspose.slides.charts/ichart/)
* Osztály [IShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)