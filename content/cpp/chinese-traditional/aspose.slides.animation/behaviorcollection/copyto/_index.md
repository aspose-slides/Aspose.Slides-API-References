---
title: CopyTo()
second_title: Aspose.Slides for C++ API 參考文件
description: "將 ICollection 的元素複製到 System::Array，從特定的 System::Array 索引開始。"
type: docs
weight: 66
url: /zh-hant/aspose.slides.animation/behaviorcollection/copyto/
---
## BehaviorCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehavior\>\>, int32_t) 方法


將 [ICollection](../../../system.collections.generic/icollection/) 的元素複製到 [System::Array](../../../system/array/)，從特定的 [System::Array](../../../system/array/) 索引開始。

```cpp
void Aspose::Slides::Animation::BehaviorCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehavior>> array, int32_t arrayIndex)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehavior](../../ibehavior/)\>\> | 從 [ICollection](../../../system.collections.generic/icollection/) 複製的元素的目的地為單維 [System::Array](../../../system/array/)。[System::Array](../../../system/array/) 必須具有零基索引。 |
| arrayIndex | **int32_t** | 複製開始時 *array* 中的零基索引。 |

## 參見

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IBehavior](../../ibehavior/)
* 類別 [BehaviorCollection](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)