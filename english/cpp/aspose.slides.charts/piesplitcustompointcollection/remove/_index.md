---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes item from collection.
type: docs
weight: 79
url: /cpp/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) method


Removes item from collection.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Data point remove to. |

### Return Value

true if item is successfully removed; otherwise, false. This method also returns false if item was not found in the [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) method


Removes item from collection by it index in parent series points collection.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Index of data point in parent series points collection. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [PieSplitCustomPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)