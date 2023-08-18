---
title: IndexOf()
second_title: Aspose.Slides for C++ API Reference
description: Determines the index of a specific item in the IList.
type: docs
weight: 40
url: /aspose.slides.animation/behaviorpropertycollection/indexof/
---
## BehaviorPropertyCollection::IndexOf(const System::SharedPtr\<IBehaviorProperty\>\&) const method


Determines the index of a specific item in the [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::SharedPtr<IBehaviorProperty> &item) const override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\& | The object to locate in the [IList](../../../system.collections.generic/ilist/). |

### Return Value

The index of *item*  if found in the list; otherwise, -1.

## BehaviorPropertyCollection::IndexOf(const System::String\&) const method


Determines the index of a specific item by property value in the [IList](../../../system.collections.generic/ilist/).

```cpp
int32_t Aspose::Slides::Animation::BehaviorPropertyCollection::IndexOf(const System::String &propertyValue) const override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | const [System::String](../../../system/string/)\& | value of the property |

### Return Value

The index of the property with the specified value

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBehaviorProperty](../../ibehaviorproperty/)
* Class [BehaviorPropertyCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)