---
title: CopyTo()
second_title: Aspose.Slides for C++ API 参考
description: "将 ICollection 的元素复制到 System::Array 中，从特定的 System::Array 索引开始。"
type: docs
weight: 66
url: /zh/aspose.slides.animation/behaviorcollection/copyto/
---
## BehaviorCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehavior\>\>, int32_t) 方法

将 [ICollection](../../../system.collections.generic/icollection/) 的元素复制到 [System::Array](../../../system/array/)，从特定的 [System::Array](../../../system/array/) 索引开始。

```cpp
void Aspose::Slides::Animation::BehaviorCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehavior>> array, int32_t arrayIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehavior](../../ibehavior/)\>\> | 一维 [System::Array](../../../system/array/)，是从 [ICollection](../../../system.collections.generic/icollection/) 复制的元素的目标。[System::Array](../../../system/array/) 必须使用零基索引。 |
| arrayIndex | **int32_t** | *array* 中的零基索引，复制从此开始。 |

## 另请参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IBehavior](../../ibehavior/)
* 类 [BehaviorCollection](../)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)