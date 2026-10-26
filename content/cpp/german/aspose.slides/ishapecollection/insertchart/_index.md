---
title: InsertChart()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt ein neues chart, initialisiert es mit Beispiel-Seriendaten und Einstellungen und fügt es an dem angegebenen Index in die shape collection ein.
type: docs
weight: 53
url: /de/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) Methode

Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -einstellungen und fügt es an dem angegebenen Index in die Shape-Collection ein.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Der Typ des zu erstellenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms, in Punkten. |
| width | **float** | Die Breite des neuen Diagramms, in Punkten. |
| height | **float** | Die Höhe des neuen Diagramms, in Punkten. |
| index | **int32_t** | Der nullbasierte Index, an dem das neue Diagramm in die Shape-Collection eingefügt wird. |

### Rückgabewert

Das neu erstellte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) Methode

Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -einstellungen und fügt es an dem angegebenen Index in die Shape-Collection ein.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Der Typ des zu erstellenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms, in Punkten. |
| width | **float** | Die Breite des neuen Diagramms, in Punkten. |
| height | **float** | Die Höhe des neuen Diagramms, in Punkten. |
| index | **int32_t** | Der nullbasierte Index, an dem das neue Diagramm in die Shape-Collection eingefügt wird. |
| initWithSample | **bool** | True, um das neue Diagramm mit Beispieldaten und -einstellungen zu initialisieren; false, um das Diagramm ohne Serien und nur mit Minimal-einstellungen zu erstellen, was die Erstellung beschleunigt. |

### Rückgabewert

Das neu erstellte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Siehe auch

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)