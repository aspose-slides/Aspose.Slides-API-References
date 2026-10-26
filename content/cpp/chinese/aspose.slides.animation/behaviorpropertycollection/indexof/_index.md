---
title: IndexOf()
second_title: Aspose.Slides for C++ API 参考文档
description: 确定 IList 中特定项的索引。
type: docs
weight: 40
url: /zh/aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const 方法


确定 [IList](../../../system.collections.generic/ilist/) 中特定项的索引。

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | 要在 [IList](../../../system.collections.generic/ilist/) 中定位的对象。 |

### 返回值

如果在列表中找到 *item*，返回其索引；否则返回 -1。

## BehaviorPropertyCollection::IndexOf(const System::String\&) const 方法


通过属性值确定 [IList](../../../system.collections.generic/ilist/) 中特定项的索引。

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | 属性的值 |

### 返回值

具有指定值的属性的索引

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IBehaviorProperty](../../ibehaviorproperty/)
* 类 [BehaviorPropertyCollection](../)
* 类 [String](../../../system/string/)
* 命名空间 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)