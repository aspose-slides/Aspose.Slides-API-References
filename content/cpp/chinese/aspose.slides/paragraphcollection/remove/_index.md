---
title: Remove()
second_title: Aspose.Slides C++ API 参考
description: 从 ICollection 中移除首次出现的特定对象。
type: docs
weight: 131
url: /zh/aspose.slides/paragraphcollection/remove/
---
## ParagraphCollection::Remove(System::SharedPtr\<IParagraph\>) 方法

从 [ICollection](../../../system.collections.generic/icollection/) 中移除首次出现的特定对象。

```cpp
bool Aspose::Slides::ParagraphCollection::Remove(System::SharedPtr<IParagraph> item) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 要从 [ICollection](../../../system.collections.generic/icollection/) 中移除的对象。 |

### 返回值

如果成功从 [ICollection](../../../system.collections.generic/icollection/) 中移除了 *item* 则返回 true；否则返回 false。如果在原始 [ICollection](../../../system.collections.generic/icollection/) 中未找到 *item*，该方法也返回 false。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IParagraph](../../iparagraph/)
* 类 [ParagraphCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)