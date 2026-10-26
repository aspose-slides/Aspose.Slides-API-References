---
title: CopyTo()
second_title: Aspose.Slides C++ API 参考
description: "将 ICollection 的元素复制到 System::Array，从特定的 System::Array 索引开始。"
type: docs
weight: 66
url: /zh/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) 方法


将 [ICollection](../../../system.collections.generic/icollection/) 的元素复制到 [System::Array](../../../system/array/)，从特定的 [System::Array](../../../system/array/) 索引开始。

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | 从 [ICollection](../../../system.collections.generic/icollection/) 复制的元素的目标的一维 [System::Array](../../../system/array/)。[System::Array](../../../system/array/) 必须具有零基索引。 |
| arrayIndex | **int32_t** | 在 *array* 中开始复制的零基索引。 |

## 另请参阅

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IBehaviorProperty](../../ibehaviorproperty/)
* 类 [BehaviorPropertyCollection](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)