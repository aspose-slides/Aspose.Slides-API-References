---
title: Insert()
second_title: Aspose.Slides for C++ API 參考
description: 在指定的索引處將新屬性插入集合。
type: docs
weight: 53
url: /zh-hant/aspose.slides.animation/behaviorpropertycollection/insert/
---
## BehaviorPropertyCollection::Insert(int32_t, const System::SharedPtr\<IBehaviorProperty\>\&) 方法

在指定的索引處將新屬性插入集合。

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::Insert(int32_t index, const System::SharedPtr<IBehaviorProperty> &item) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 應插入新屬性的索引。 |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | 要新增的屬性。 |

## BehaviorPropertyCollection::Insert(int32_t, System::String) 方法

在指定的索引處將新屬性（具有指定的屬性值）插入集合。

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::Insert(int32_t index, System::String propertyValue) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 應插入新屬性的索引。 |
| propertyValue | [System::String](../../../system/string/) | 要新增之屬性的值。 |

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IBehaviorProperty](../../ibehaviorproperty/)
* 類別 [BehaviorPropertyCollection](../)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)