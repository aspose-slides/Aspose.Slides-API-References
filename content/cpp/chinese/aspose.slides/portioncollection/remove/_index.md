---
title: Remove()
second_title: Aspose.Slides C++ API 参考
description: 从 ICollection 中删除特定对象的首次出现。
type: docs
weight: 131
url: /zh/aspose.slides/portioncollection/remove/
---
## PortionCollection::Remove(System::SharedPtr\<IPortion\>) 方法

从 [ICollection](../../../system.collections.generic/icollection/) 中删除特定对象的首次出现。

```cpp
bool Aspose::Slides::PortionCollection::Remove(System::SharedPtr<IPortion> item) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | 要从 [ICollection](../../../system.collections.generic/icollection/) 中删除的对象。 |

### 返回值

如果 *item* 已成功从 [ICollection](../../../system.collections.generic/icollection/) 中删除则返回 true；否则返回 false。如果在原始 [ICollection](../../../system.collections.generic/icollection/) 中未找到 *item*，该方法也返回 false。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPortion](../../iportion/)
* 类 [PortionCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)