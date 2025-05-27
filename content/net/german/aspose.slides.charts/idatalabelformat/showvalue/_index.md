---
title: ShowValue
second_title: Aspose.Slides für .NET API-Referenz
description: Repräsentiert das Verhalten der Anzeige des prozentualen Wertes des Datenbeschriftungsformats eines bestimmten Diagramms. True zeigt den prozentualen Wert an. False, um ihn auszublenden. Lese-/Schreib-Boolean.
type: docs
weight: 150
url: /de/aspose.slides.charts/idatalabelformat/showvalue/
---

## IDataLabelFormat.ShowValue-Eigenschaft

Repräsentiert das Verhalten der Anzeige des prozentualen Wertes des Datenbeschriftungsformats eines bestimmten Diagramms. True zeigt den prozentualen Wert an. False, um ihn auszublenden. Lese-/Schreib-Boolean.

```csharp
public bool ShowValue { get; set; }
```

### Bemerkungen

Wenn der Elternteil dieses DataLabelFormat-Objekts eine DataLabelCollection von Datenbeschriftungen ist, wird durch diese Eigenschaft der Standardwert der ShowValue-Eigenschaft für die neuen Datenbeschriftungen in der DataLabelCollection festgelegt. Das Setzen dieser Eigenschaft mit einem Wert setzt auch diesen Wert für die ShowValue-Eigenschaft aller Datenbeschriftungen in der DataLabelCollection (d.h. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" führt dazu, dass alle DataLabels[i].ShowValue gleich val sind).

### Siehe auch

* Schnittstelle [IDataLabelFormat](../../idatalabelformat)
* Namespace [Aspose.Slides.Charts](../../idatalabelformat)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->