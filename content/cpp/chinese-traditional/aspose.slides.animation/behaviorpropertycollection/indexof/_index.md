---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考
description: 確定 IList 中特定項目的索引。
type: docs
weight: 40
url: /zh-hant/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const 方法

確定特定項目在 [IList](../../../system.collections.generic/ilist/) 中的索引。

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | 要在 [IList](../../../system.collections.generic/ilist/) 中定位的物件。 |

### 傳回值

如果在列表中找到 *item*，則傳回其索引；否則傳回 -1。

## BehaviorPropertyCollection::IndexOf(const System::String\&) const 方法

確定特定項目依屬性值在 [IList](../../../system.collections.generic/ilist/) 中的索引。

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | 屬性的值 |

### 傳回值

傳回具有指定值的屬性的索引

## 另請參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IBehaviorProperty](../../ibehaviorproperty/)
* 類別 [BehaviorPropertyCollection](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)