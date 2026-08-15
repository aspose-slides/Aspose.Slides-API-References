---
title: CopyTo()
second_title: Aspose.Slides for C++ API 參考
description: "將 ICollection 的元素複製到 System::Array，從特定的 System::Array 索引開始。"
type: docs
weight: 118
url: /zh-hant/aspose.slides.charts/piesplitcustompointcollection/copyto/
---
## PieSplitCustomPointCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IChartDataPoint\>\>, int32_t) 方法

將 [ICollection](../../../system.collections.generic/icollection/) 的元素複製到 [System::Array](../../../system/array/)，從特定的 [System::Array](../../../system/array/) 索引開始。

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IChartDataPoint>> array, int32_t arrayIndex) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\> | 從 [ICollection](../../../system.collections.generic/icollection/) 複製的元素的目標是一維 [System::Array](../../../system/array/)。[System::Array](../../../system/array/) 必須使用零基索引。 |
| arrayIndex | **int32_t** | 在 *array* 中開始複製的零基索引。 |

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IChartDataPoint](../../ichartdatapoint/)
* 類別 [PieSplitCustomPointCollection](../)
* 命名空間 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)