---
title: Contains()
second_title: Aspose.Slides for C++ API 參考
description: 判斷 ICollection 是否包含特定值。
type: docs
weight: 118
url: /zh-hant/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const 方法

判斷 [ICollection](../../../system.collections.generic/icollection/) 是否包含特定值。

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | 要在 [ICollection](../../../system.collections.generic/icollection/) 中定位的屬性。 |

### 傳回值

若在 [ICollection](../../../system.collections.generic/icollection/) 中找到 *item*，則傳回 true；否則傳回 false。

## BehaviorPropertyCollection::Contains(const System::String\&) const 方法

判斷 [ICollection](../../../system.collections.generic/icollection/) 是否包含特定值。

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | 要在 [ICollection](../../../system.collections.generic/icollection/) 中定位的屬性值。 |

### 傳回值

若在 [ICollection](../../../system.collections.generic/icollection/) 中找到 *propertyValue*，則傳回 true；否則傳回 false。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IBehaviorProperty](../../ibehaviorproperty/)
* 類別 [BehaviorPropertyCollection](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)