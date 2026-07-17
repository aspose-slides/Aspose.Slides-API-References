---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides for C++ API 参考
description: "如果集合已经包含索引为 index 的数据点，则返回该数据点。如果集合不包含索引为 index ==N 的数据点（当此集合中的数据点数量小于或等于 N 时），则添加缺失的数据点并返回最后一个（即具有请求索引的那一个）。例如，集合的索引为 {0, 1, 2}，请求的索引为 5。然后方法添加缺失的数据点：{0, 1, 2, 3, 4, 5}。并返回索引为 5 的数据点。"
type: docs
weight: 170
url: /zh/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) 方法

如果集合已经包含索引为 *index* 的数据点，则返回该数据点。如果集合不包含索引为 *index* ==N 的数据点（当此集合中的数据点数量小于或等于 N 时），则添加缺失的数据点并返回最后一个（即具有请求索引的那一个）。例如，集合的索引为 {0, 1, 2}，请求的索引为 5。然后方法添加缺失的数据点：{0, 1, 2, 3, 4, 5}。并返回索引为 5 的数据点。

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **uint32_t** | 索引。 |

### 返回值

返回具有请求索引的数据点。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [ChartDataPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)