---
title: Remove()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort ett objekt från samlingen.
type: docs
weight: 79
url: /sv/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) metod


Tar bort ett objekt från samlingen.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Datapunkt att ta bort. |

### Returvärde

true om objektet har tagits bort framgångsrikt; annars false. Denna metod returnerar också false om objektet inte hittades i [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) metod


Tar bort ett objekt från samlingen efter dess index i förälderns seriepunktssamling.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Index för datapunkt i förälderns seriepunktssamling. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChartDataPoint](../../ichartdatapoint/)
* Klass [PieSplitCustomPointCollection](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)