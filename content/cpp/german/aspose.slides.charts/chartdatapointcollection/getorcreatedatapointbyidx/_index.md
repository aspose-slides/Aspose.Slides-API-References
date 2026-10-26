---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides für C++ API Referenz
description: "Wenn die Sammlung bereits einen Datenpunkt mit dem Index index enthält, gibt sie diesen Datenpunkt zurück. Wenn die Sammlung keinen Datenpunkt mit dem Index index ==N (wenn die Anzahl der Datenpunkte in dieser Sammlung kleiner oder gleich N ist) enthält, fügt sie fehlende Datenpunkte hinzu und gibt den letzten zurück (der den angeforderten Index hat). Zum Beispiel sind die Indizes der Sammlung {0, 1, 2} und der angeforderte Index ist 5. Dann fügt die Methode fehlende Datenpunkte hinzu: {0, 1, 2, 3, 4, 5}. Und gibt den Datenpunkt mit Index 5 zurück."
type: docs
weight: 170
url: /de/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) Methode

Wenn die Sammlung bereits einen Datenpunkt mit dem Index *index* enthält, gibt sie diesen Datenpunkt zurück. Wenn die Sammlung keinen Datenpunkt mit dem Index *index* ==N enthält (wenn die Anzahl der Datenpunkte in dieser Sammlung kleiner oder gleich N ist), fügt sie fehlende Datenpunkte hinzu und gibt den letzten zurück (der den angeforderten Index hat). Zum Beispiel sind die Indizes der Sammlung {0, 1, 2} und der angeforderte Index ist 5. Dann fügt die Methode fehlende Datenpunkte hinzu: {0, 1, 2, 3, 4, 5}. Und gibt den Datenpunkt mit Index 5 zurück.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **uint32_t** | Index. |

### Rückgabewert

Gibt den Datenpunkt mit dem angeforderten Index zurück.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataPoint](../../ichartdatapoint/)
* Klasse [ChartDataPointCollection](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)