---
title: GetOrCreateDataPointByIdx
second_title: Aspose.Slides für .NET-API-Referenz
description: Wenn Sammlung bereits Datenpunkt mit Index enthältindex gibt dann diesen Datenpunkt zurück. Wenn Sammlung keinen Datenpunkt mit Index enthältindex N wenn die Anzahl der Datenpunkte in dieser Sammlung kleiner oder gleich N ist fügt dann mangelhafte Datenpunkte hinzu und gibt den letzten zurück der den Index angefordert hat. Sammlungsindizes sind beispielsweise 0 1 2 und der angeforderte Index ist 5. Dann fügt die Methode fehlerhafte Datenpunkte hinzu 0 1 2 3 4 5. Und gibt Datenpunkt mit Index 5. zurück
type: docs
weight: 300
url: /de/net/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection.GetOrCreateDataPointByIdx method

Wenn Sammlung bereits Datenpunkt mit Index enthält*index* gibt dann diesen Datenpunkt zurück. Wenn Sammlung keinen Datenpunkt mit Index enthält*index* ==N (wenn die Anzahl der Datenpunkte in dieser Sammlung kleiner oder gleich N ist) fügt dann mangelhafte Datenpunkte hinzu und gibt den letzten zurück (der den Index angefordert hat). Sammlungsindizes sind beispielsweise {0, 1, 2} und der angeforderte Index ist 5. Dann fügt die Methode fehlerhafte Datenpunkte hinzu: {0, 1, 2, 3, 4, 5}. Und gibt Datenpunkt mit Index 5. zurück

```csharp
public IChartDataPoint GetOrCreateDataPointByIdx(uint index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | UInt32 | Index. |

### Rückgabewert

Gibt Datenpunkt mit angefordertem Index zurück.

### Siehe auch

* interface [IChartDataPoint](../../ichartdatapoint)
* class [ChartDataPointCollection](../../chartdatapointcollection)
* namensraum [Aspose.Slides.Charts](../../chartdatapointcollection)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->