---
title: InsertChart()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an dem angegebenen Index in die ShapeCollection ein.
type: docs
weight: 92
url: /de/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) Methode


Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an dem angegebenen Index in die ShapeCollection ein.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Der Typ des zu erstellenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms, in Punkten. |
| width | **float** | Die Breite des neuen Diagramms, in Punkten. |
| height | **float** | Die Höhe des neuen Diagramms, in Punkten. |
| index | **int32_t** | Der nullbasierte Index, an dem das neue Diagramm in die ShapeCollection eingefügt wird. |

### Rückgabewert

Das neu erstellte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) Methode


Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an dem angegebenen Index in die ShapeCollection ein.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Der Typ des zu erstellenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms, in Punkten. |
| width | **float** | Die Breite des neuen Diagramms, in Punkten. |
| height | **float** | Die Höhe des neuen Diagramms, in Punkten. |
| index | **int32_t** | Der nullbasierte Index, an dem das neue Diagramm in die ShapeCollection eingefügt wird. |
| initWithSample | **bool** | True, um das neue Diagramm mit Beispieldaten und -einstellungen zu initialisieren; false, um das Diagramm ohne Serien und nur mit minimalen Einstellungen zu erstellen, was die Erstellung beschleunigt. |

### Rückgabewert

Das neu erstellte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Siehe auch

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChart](../../../aspose.slides.charts/ichart/)
* Klasse [ShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)