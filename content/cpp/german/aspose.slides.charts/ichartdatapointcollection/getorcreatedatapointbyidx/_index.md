---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides für C++ API-Referenz
description: "Wenn die Sammlung bereits einen Datenpunkt mit dem Index index enthält, wird dieser Datenpunkt zurückgegeben. Wenn die Sammlung keinen Datenpunkt mit dem Index index ==N enthält (wenn die Anzahl der Datenpunkte in dieser Sammlung kleiner oder gleich N ist), werden fehlende Datenpunkte hinzugefügt und der letzte zurückgegeben (der den gewünschten Index hat). Zum Beispiel sind die Indizes der Sammlung {0, 1, 2} und der gewünschte Index ist 5. Dann fügt die Methode fehlende Datenpunkte hinzu: {0, 1, 2, 3, 4, 5}. Und gibt den Datenpunkt mit Index 5 zurück."
type: docs
weight: 131
url: /de/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) Methode

Falls die Sammlung bereits einen Datenpunkt mit dem Index *index* enthält, gibt sie diesen Datenpunkt zurück. Falls die Sammlung keinen Datenpunkt mit dem Index *index* ==N enthält (wenn die Anzahl der Datenpunkte in dieser Sammlung kleiner oder gleich N ist), werden fehlende Datenpunkte hinzugefügt und der letzte zurückgegeben (der den gewünschten Index hat). Zum Beispiel sind die Indizes der Sammlung {0, 1, 2} und der gewünschte Index ist 5. Dann fügt die Methode fehlende Datenpunkte hinzu: {0, 1, 2, 3, 4, 5}. Und gibt den Datenpunkt mit Index 5 zurück.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **uint32_t** | Index. |

### Rückgabewert

Gibt den Datenpunkt mit dem gewünschten Index zurück.

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataPoint](../../ichartdatapoint/)
* Klasse [IChartDataPointCollection](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)