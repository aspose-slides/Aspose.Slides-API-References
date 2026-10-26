---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides voor C++ API-referentie
description: "Als de collectie al een datapunt bevat met index index dan retourneert deze datapunt. Als de collectie geen datapunt bevat met index index ==N (wanneer het aantal datapunten in deze collectie kleiner of gelijk is aan N) dan voegt het ontbrekende datapunten toe en retourneert het laatste (dat de gevraagde index heeft). Bijvoorbeeld, de indexen van de collectie zijn {0, 1, 2}, en de gevraagde index is 5. Dan voegt de methode ontbrekende datapunten toe: {0, 1, 2, 3, 4, 5}. En retourneert het datapunt met index 5."
type: docs
weight: 170
url: /nl/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) methode


Als de collectie al een datapunt bevat met index *index* dan wordt dit datapunt geretourneerd. Als de collectie geen datapunt bevat met index *index* ==N (wanneer het aantal datapunten in deze collectie kleiner of gelijk is aan N) dan worden ontbrekende datapunten toegevoegd en wordt de laatste geretourneerd (die de gevraagde index heeft). Bijvoorbeeld, de collectie-indexen zijn {0, 1, 2}, en de gevraagde index is 5. Dan voegt de methode ontbrekende datapunten toe: {0, 1, 2, 3, 4, 5}. En retourneert datapunt met index 5.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **uint32_t** | Index. |

### Retourwaarde

Retourneert datapunt met de gevraagde index.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataPoint](../../ichartdatapoint/)
* Klasse [ChartDataPointCollection](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)