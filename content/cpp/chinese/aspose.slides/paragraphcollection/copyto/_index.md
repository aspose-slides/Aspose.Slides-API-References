---
title: CopyTo()
second_title: Aspose.Slides for C++ API 参考
description: "将 ICollection 的元素复制到 System::Array 中，从特定的 System::Array 索引开始。"
type: docs
weight: 105
url: /zh/aspose.slides/paragraphcollection/copyto/
---
## ParagraphCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IParagraph\>\>, int32_t) 方法


复制 [ICollection](../../../system.collections.generic/icollection/) 的元素到 [System::Array](../../../system/array/)，从特定的 [System::Array](../../../system/array/) 索引开始。

```cpp
void Aspose::Slides::ParagraphCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IParagraph>> array, int32_t arrayIndex)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\>\> | 一维 [System::Array](../../../system/array/)，是从 [ICollection](../../../system.collections.generic/icollection/) 复制的元素的目标。[System::Array](../../../system/array/) 必须使用零基索引。 |
| arrayIndex | **int32_t** | 在 *array* 中开始复制的零基索引。 |

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IParagraph](../../iparagraph/)
* 类 [ParagraphCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)