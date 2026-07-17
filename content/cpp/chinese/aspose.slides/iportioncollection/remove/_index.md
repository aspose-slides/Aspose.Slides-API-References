---
title: Remove()
second_title: Aspose.Slides C++ API 参考
description: 从 ICollection 中移除特定对象的第一次出现。
type: docs
weight: 92
url: /zh/aspose.slides/iportioncollection/remove/
---
## IPortionCollection::Remove(System::SharedPtr\<IPortion\>) 方法

从 [ICollection](../../../system.collections.generic/icollection/) 中移除特定对象的第一次出现。

```cpp
virtual bool Aspose::Slides::IPortionCollection::Remove(System::SharedPtr<IPortion> item)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | 从 [ICollection](../../../system.collections.generic/icollection/) 中要移除的对象。 |

### 返回值

如果 *item* 已成功从 [ICollection](../../../system.collections.generic/icollection/) 中移除则返回 true；否则返回 false。如果在原始 [ICollection](../../../system.collections.generic/icollection/) 中未找到 *item*，此方法同样返回 false。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPortion](../../iportion/)
* 类 [IPortionCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)