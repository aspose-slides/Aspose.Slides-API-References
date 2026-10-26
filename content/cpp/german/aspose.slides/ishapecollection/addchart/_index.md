---
title: AddChart()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten von Serien und Einstellungen und fügt es am Ende der Shape-Sammlung hinzu.
type: docs
weight: 27
url: /de/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) Methode

Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten von Serien und Einstellungen und fügt es am Ende der Shape-Sammlung hinzu.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Der Typ des hinzuzufügenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms, in Punkten. |
| width | **float** | Die Breite des Diagramms, in Punkten. |
| height | **float** | Die Höhe des Diagramms, in Punkten. |

### Rückgabewert

Das neu erstellte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) Methode

Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten von Serien und Einstellungen und fügt es am Ende der Shape-Sammlung hinzu.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Der Typ des hinzuzufügenden Diagramms. |
| x | **float** | Die x-Koordinate des neuen Diagramms, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Diagramms, in Punkten. |
| width | **float** | Die Breite des Diagramms, in Punkten. |
| height | **float** | Die Höhe des Diagramms, in Punkten. |
| initWithSample | **bool** | True, um das neue Diagramm mit Beispieldaten von Serien und Einstellungen zu initialisieren; false, um das Diagramm ohne Serien und nur mit minimalen Einstellungen zu erstellen, wodurch die Erstellung schneller ist. |

### Rückgabewert

Das neu erstellte [Charts::IChart](../../../aspose.slides.charts/ichart/).

## Siehe auch

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChart](../../../aspose.slides.charts/ichart/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)