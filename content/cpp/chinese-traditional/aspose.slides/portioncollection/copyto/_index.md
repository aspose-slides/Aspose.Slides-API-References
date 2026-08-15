---
title: CopyTo()
second_title: Aspose.Slides for C++ API 參考文件
description: "將 ICollection 的元素複製到 System::Array，從特定的 System::Array 索引開始。"
type: docs
weight: 118
url: /zh-hant/aspose.slides/portioncollection/copyto/
---
## PortionCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IPortion\>\>, int32_t) 方法

將 [ICollection](../../../system.collections.generic/icollection/) 的元素複製到 [System::Array](../../../system/array/)，從特定的 [System::Array](../../../system/array/) 索引開始。

```cpp
void Aspose::Slides::PortionCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IPortion>> array, int32_t arrayIndex)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\>\> | 一維的 [System::Array](../../../system/array/)，作為從 [ICollection](../../../system.collections.generic/icollection/) 複製的元素的目的地。[System::Array](../../../system/array/) 必須使用零基索引。 |
| arrayIndex | **int32_t** | 在 *array* 中開始複製的零基索引。 |

## 另請參閱

* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPortion](../../iportion/)
* 類別 [PortionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)