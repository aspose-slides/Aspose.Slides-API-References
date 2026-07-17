---
title: Insert()
second_title: Aspose.Slides C++ API 参考
description: 在指定索引处向集合插入新属性。
type: docs
weight: 53
url: /zh/aspose.slides.animation/behaviorpropertycollection/insert/
---
## BehaviorPropertyCollection::Insert(int32_t, const System::SharedPtr\<IBehaviorProperty\>\&) 方法

在指定索引处向集合插入一个新属性。

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::Insert(int32_t index, const System::SharedPtr<IBehaviorProperty> &item) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新属性应插入的位置索引。 |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | 要添加的属性。 |

## BehaviorPropertyCollection::Insert(int32_t, System::String) 方法

在指定索引处向集合插入一个新属性（使用指定的属性值）。

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::Insert(int32_t index, System::String propertyValue) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新属性应插入的位置索引。 |
| propertyValue | [System::String](../../../system/string/) | 要添加的属性的值。 |

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IBehaviorProperty](../../ibehaviorproperty/)
* 类 [BehaviorPropertyCollection](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)