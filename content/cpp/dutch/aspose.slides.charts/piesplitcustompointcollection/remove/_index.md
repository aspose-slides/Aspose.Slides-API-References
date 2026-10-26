---
title: Remove()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert item uit de collectie.
type: docs
weight: 79
url: /nl/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) methode


Verwijdert item uit de collectie.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Datapunt om te verwijderen. |

### Retourwaarde

true als het item succesvol is verwijderd; anders false. Deze methode retourneert ook false als het item niet werd gevonden in de [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) methode


Verwijdert item uit de collectie op basis van de index in de puntenverzameling van de bovenliggende serie.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Index van datapunt in de puntenverzameling van de bovenliggende serie. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataPoint](../../ichartdatapoint/)
* Klasse [PieSplitCustomPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)