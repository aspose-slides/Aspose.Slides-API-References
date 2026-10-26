---
title: CopyTo()
second_title: Aspose.Slides for C++ API 参考
description: "将 ICollection 的元素复制到 System::Array 中，从特定的 System::Array 索引开始。"
type: docs
weight: 118
url: /zh/aspose.slides.charts/piesplitcustompointcollection/copyto/
---
## PieSplitCustomPointCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IChartDataPoint\>\>, int32_t) 方法

将 [ICollection](../../../system.collections.generic/icollection/) 的元素复制到 [System::Array](../../../system/array/)，从特定的 [System::Array](../../../system/array/) 索引开始。

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IChartDataPoint>> array, int32_t arrayIndex) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\> | 从 [ICollection](../../../system.collections.generic/icollection/) 复制的元素的目标的一维 [System::Array](../../../system/array/)。[System::Array](../../../system/array/) 必须采用零基索引。 |
| arrayIndex | **int32_t** | 在 *array* 中开始复制的零基索引。 |

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IChartDataPoint](../../ichartdatapoint/)
* 类 [PieSplitCustomPointCollection](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)