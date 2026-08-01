---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides voor C++ API-referentie
description: "Als de collectie al een gegevenspunt bevat met index index, dan retourneert het dit gegevenspunt. Als de collectie geen gegevenspunt bevat met index index ==N (wanneer het aantal gegevenspunten in deze collectie kleiner of gelijk is aan N), dan voegt het ontbrekende gegevenspunten toe en retourneert het laatste (dat de gevraagde index heeft). Bijvoorbeeld, de indexen van de collectie zijn {0, 1, 2}, en de gevraagde index is 5. Vervolgens voegt de methode ontbrekende gegevenspunten toe: {0, 1, 2, 3, 4, 5}. En retourneert het gegevenspunt met index 5."
type: docs
weight: 131
url: /nl/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) methode


Als de collectie al een gegevenspunt bevat met index *index* vervolgens retourneert dit gegevenspunt. Als de collectie geen gegevenspunt bevat met index *index* ==N (wanneer het aantal gegevenspunten in deze collectie kleiner of gelijk is aan N) voegt het ontbrekende gegevenspunten toe en retourneert het laatste (dat de gevraagde index heeft). Bijvoorbeeld, de indexen van de collectie zijn {0, 1, 2}, en de gevraagde index is 5. Vervolgens voegt de methode ontbrekende gegevenspunten toe: {0, 1, 2, 3, 4, 5}. En retourneert het gegevenspunt met index 5.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **uint32_t** | Index. |

### Retourwaarde

Retourneert het gegevenspunt met de gevraagde index.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)