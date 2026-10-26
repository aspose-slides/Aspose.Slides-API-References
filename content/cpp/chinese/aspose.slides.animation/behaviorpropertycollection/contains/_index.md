---
title: Contains()
second_title: Aspose.Slides for C++ API 参考
description: 确定 ICollection 是否包含特定值。
type: docs
weight: 118
url: /zh/aspose.slides.animation/behaviorpropertycollection/contains/
---
## BehaviorPropertyCollection::Contains(const System::SharedPtr\<IBehaviorProperty\>\&) const 方法

确定 [ICollection](../../../system.collections.generic/icollection/) 是否包含特定值。

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::SharedPtr<IBehaviorProperty> &item) const override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | 要在 [ICollection](../../../system.collections.generic/icollection/) 中定位的属性。 |

### 返回值

如果在 [ICollection](../../../system.collections.generic/icollection/) 中找到 *item* 则返回 true；否则返回 false。

## BehaviorPropertyCollection::Contains(const System::String\&) const 方法

确定 [ICollection](../../../system.collections.generic/icollection/) 是否包含特定值。

```cpp
bool Aspose::Slides::Animation::BehaviorPropertyCollection::Contains(const System::String &propertyValue) const override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | 要在 [ICollection](../../../system.collections.generic/icollection/) 中定位的属性值。 |

### 返回值

如果在 [ICollection](../../../system.collections.generic/icollection/) 中找到 *propertyValue* 则返回 true；否则返回 false。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IBehaviorProperty](../../ibehaviorproperty/)
* 类 [BehaviorPropertyCollection](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::Animation](../../)
* 库 [Aspose.Slides](../../../)