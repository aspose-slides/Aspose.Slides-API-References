---
title: IndexOf()
second_title: Aspose.Slides for C++ API 参考文档
description: 在整个集合中搜索指定的 ChartSeries 并返回首次出现的零基索引
type: docs
weight: 79
url: /zh/aspose.slides.charts/chartseriescollection/indexof/
---
## ChartSeriesCollection::IndexOf(System::SharedPtr\<IChartSeries\>) 方法

搜索指定的 [ChartSeries](../../chartseries/)，并返回其在整个 Collection 中首次出现的零基索引

```cpp
int32_t Aspose::Slides::Charts::ChartSeriesCollection::IndexOf(System::SharedPtr<IChartSeries> value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartSeries](../../ichartseries/)\> | [Chart](../../chart/) 系列值。 |

### 返回值

如果找到，则返回 value 在整个 CollectionBase 中首次出现的零基索引；否则返回 -1。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartSeries](../../ichartseries/)
* 类 [ChartSeriesCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)