---
title: Remove()
second_title: Aspose.Slides C++ API 參考
description: 從 ICollection 中移除特定物件的第一次出現。
type: docs
weight: 131
url: /zh-hant/aspose.slides/portioncollection/remove/
---
## PortionCollection::Remove(System::SharedPtr\<IPortion\>) 方法

從 [ICollection](../../../system.collections.generic/icollection/) 中移除特定物件的第一次出現。

```cpp
bool Aspose::Slides::PortionCollection::Remove(System::SharedPtr<IPortion> item) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | 要從 [ICollection](../../../system.collections.generic/icollection/) 中移除的物件。 |

### 回傳值

如果成功從 [ICollection](../../../system.collections.generic/icollection/) 中移除 *item*，則回傳 true；否則回傳 false。如果在原始的 [ICollection](../../../system.collections.generic/icollection/) 中找不到 *item*，此方法也會回傳 false。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [PortionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)