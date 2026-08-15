---
title: CopyTo()
second_title: Aspose.Slides for C++ API 參考文件
description: "將 ICollection 的元素複製到 System::Array，從特定的 System::Array 索引開始。"
type: docs
weight: 66
url: /zh-hant/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) 方法

將 [ICollection](../../../system.collections.generic/icollection/) 的元素複製到 [System::Array](../../../system/array/)，從特定的 [System::Array](../../../system/array/) 索引開始。

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | 單維的 [System::Array](../../../system/array/)，作為從 [ICollection](../../../system.collections.generic/icollection/) 複製的元素的目標。[System::Array](../../../system/array/) 必須使用零基索引。 |
| arrayIndex | **int32_t** | 在 *array* 中開始複製的零基索引。 |

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IBehaviorProperty](../../ibehaviorproperty/)
* 類別 [BehaviorPropertyCollection](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)