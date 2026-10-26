---
title: Remove()
second_title: Aspose.Slides for C++ API 參考文件
description: 從 ICollection 中移除特定物件的第一次出現。
type: docs
weight: 92
url: /zh-hant/aspose.slides/iportioncollection/remove/
---
## IPortionCollection::Remove(System::SharedPtr\<IPortion\>) 方法

從 [ICollection](../../../system.collections.generic/icollection/) 中移除特定物件的第一次出現。

```cpp
virtual bool Aspose::Slides::IPortionCollection::Remove(System::SharedPtr<IPortion> item)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | 要從 [ICollection](../../../system.collections.generic/icollection/) 中移除的物件。 |

### 返回值

如果成功從 [ICollection](../../../system.collections.generic/icollection/) 中移除 *item*，則返回 true；否則返回 false。若在原始 [ICollection](../../../system.collections.generic/icollection/) 中找不到 *item*，此方法也會返回 false。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IPortion](../../iportion/)
* 類別 [IPortionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)