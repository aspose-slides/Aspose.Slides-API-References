---
title: CopyTo()
second_title: Aspose.Slides for C++ API 参考
description: "将 ICollection 的元素复制到 System::Array 中，从特定的 System::Array 索引开始。"
type: docs
weight: 118
url: /zh/aspose.slides/portioncollection/copyto/
---
## PortionCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IPortion\>\>, int32_t) 方法

将 [ICollection](../../../system.collections.generic/icollection/) 的元素复制到 [System::Array](../../../system/array/)，从特定的 [System::Array](../../../system/array/) 索引开始。

```cpp
void Aspose::Slides::PortionCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IPortion>> array, int32_t arrayIndex)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\>\> | 从 [ICollection](../../../system.collections.generic/icollection/) 复制的元素的目标的一维 [System::Array](../../../system/array/)。[System::Array](../../../system/array/) 必须使用零基索引。 |
| arrayIndex | **int32_t** | 在 *array* 中开始复制的零基索引。 |

## 另请参见

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [PortionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)