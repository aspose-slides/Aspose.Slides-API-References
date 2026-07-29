---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides för C++ API-referens
description: "Om samlingen redan innehåller en datapunkt med index index returneras denna datapunkt. Om samlingen inte innehåller en datapunkt med index index ==N (när antalet datapunkter i samlingen är mindre än eller lika med N) läggs saknade datapunkter till och den sista (som har det begärda indexet) returneras. Till exempel är samlingens index {0, 1, 2}, och det begärda indexet är 5. Då lägger metoden till saknade datapunkter: {0, 1, 2, 3, 4, 5}. Och returnerar datapunkten med index 5."
type: docs
weight: 131
url: /sv/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) metod

Om samlingen redan innehåller en datapunkt med index *index* returnerar den denna datapunkt. Om samlingen inte innehåller en datapunkt med index *index* ==N (när antalet datapunkter i samlingen är mindre än eller lika med N) lägger den till saknade datapunkter och returnerar den sista (som har det begärda indexet). Till exempel är samlingens index {0, 1, 2}, och det begärda indexet är 5. Då lägger metoden till saknade datapunkter: {0, 1, 2, 3, 4, 5}. Och returnerar datapunkten med index 5.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **uint32_t** | Index. |

### Returvärde

Returnerar datapunkten med det begärda indexet.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataPoint](../../ichartdatapoint/)
* Klass [IChartDataPointCollection](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)