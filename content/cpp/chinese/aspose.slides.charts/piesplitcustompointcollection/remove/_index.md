---
title: Remove()
second_title: Aspose.Slides for C++ API 参考
description: 从集合中删除项。
type: docs
weight: 79
url: /zh/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) 方法

从集合中删除项。

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | 要删除的数据点。 |

### 返回值

如果成功删除项则返回 true；否则返回 false。如果在 [System::Collections::Generic::List](../../../system.collections.generic/list/){T} 中未找到项，也返回 false。

## PieSplitCustomPointCollection::Remove(int32_t) 方法

通过在父系列点集合中的索引从集合中删除项。

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataPointIndex | **int32_t** | 父系列点集合中数据点的索引。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [PieSplitCustomPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)