---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides C++ API 参考
description: "如果集合已经包含索引为 index 的数据点，则返回该数据点。如果集合不包含索引为 index ==N 的数据点（当该集合中的数据点数量小于或等于 N 时），则会添加缺失的数据点并返回最后一个（即具有请求索引的那个）。例如，集合的索引为 {0, 1, 2}，请求的索引为 5。然后方法会添加缺失的数据点：{0, 1, 2, 3, 4, 5}。并返回索引为 5 的数据点。"
type: docs
weight: 131
url: /zh/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) 方法


如果集合已经包含索引为 *index* 的数据点，则返回该数据点。如果集合不包含索引为 *index* ==N 的数据点（当该集合中的数据点数量小于或等于 N 时），则会添加缺失的数据点并返回最后一个（即具有请求索引的那个）。例如，集合的索引为 {0, 1, 2}，请求的索引为 5。然后方法会添加缺失的数据点：{0, 1, 2, 3, 4, 5}。并返回索引为 5 的数据点。

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **uint32_t** | 索引。 |

### 返回值

返回具有请求索引的数据点。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [IChartDataPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)