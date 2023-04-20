---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides for C++ API Reference
description: "If collection already contains data point with index index  then returns this data point. If collection doesn't contains data point with index index ==N (when number of data points in this collection is less or equal then N) then adds deficient data points and returns last (which has requested index). For example, collection indexes are {0, 1, 2}, and requested index is 5. Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5."
type: docs
weight: 131
url: /cpp/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) method


If collection already contains data point with index *index*  then returns this data point. If collection doesn't contains data point with index *index* ==N (when number of data points in this collection is less or equal then N) then adds deficient data points and returns last (which has requested index). For example, collection indexes are {0, 1, 2}, and requested index is 5. Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **uint32_t** | Index. |

### Return Value

Returns data point with requested index.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [IChartDataPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)